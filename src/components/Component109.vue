<template>
  <div class="component-10-9">
    <div class="container-673">
      <div class="container-674">
        <container9 :children="container9Props.children" />
        <div class="github valign-text-middle taviraj-semi-bold-white-12px">{{ github }}</div>
      </div>
    </div>
  </div>
</template>

<script>
import Container9 from "./Container9";
export default {
  name: "Component109",
  components: {
    Container9,
  },
  props: ["github", "container9Props"],
};
</script>

<style>
.component-10-9 {
  align-items: center;
  background-color: var(--ebony);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.container-673 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.container-674 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  gap: 3.99px;
  position: relative;
  width: 100%;
}

.github {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
