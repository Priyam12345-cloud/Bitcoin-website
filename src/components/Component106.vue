<template>
  <article class="component-10-6">
    <div class="container-666">
      <div class="container-667">
        <container9 :children="container9Props.children" />
        <div class="facebook valign-text-middle wwwcoingeckocomintersemi-bold-12">{{ facebook }}</div>
      </div>
    </div>
  </article>
</template>

<script>
import Container9 from "./Container9";
export default {
  name: "Component106",
  components: {
    Container9,
  },
  props: ["facebook", "container9Props"],
};
</script>

<style>
.component-10-6 {
  align-items: center;
  background-color: var(--ebony);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.container-666 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.container-667 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  gap: 4px;
  position: relative;
  width: 100%;
}

.facebook {
  color: var(--dhancowhite);
  font-weight: 600;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
