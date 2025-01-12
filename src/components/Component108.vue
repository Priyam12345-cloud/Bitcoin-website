<template>
  <div class="component-10-8">
    <div class="container-671">
      <div class="container-672">
        <component16 :className="component16Props.className" :container62Props="component16Props.container62Props" />
        <div class="twitter-1 valign-text-middle taviraj-semi-bold-white-12px">{{ twitter }}</div>
      </div>
    </div>
  </div>
</template>

<script>
import Component16 from "./Component16";
export default {
  name: "Component108",
  components: {
    Component16,
  },
  props: ["twitter", "component16Props"],
};
</script>

<style>
.component-10-8 {
  align-items: center;
  background-color: var(--ebony);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.container-671 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.container-672 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  gap: 4px;
  position: relative;
  width: 100%;
}

.twitter-1 {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
