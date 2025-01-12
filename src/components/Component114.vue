<template>
  <div class="component-11-12">
    <div class="container-675">
      <div class="container-676">
        <div class="text-80 valign-text-middle taviraj-semi-bold-white-12px">{{ text }}</div>
        <component162 />
      </div>
    </div>
  </div>
</template>

<script>
import Component162 from "./Component162";
export default {
  name: "Component114",
  components: {
    Component162,
  },
  props: ["text"],
};
</script>

<style>
.component-11-12 {
  align-items: center;
  background-color: var(--ebony);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.container-675 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 0px 0px 2px;
  position: relative;
}

.container-676 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  gap: 4px;
  position: relative;
  width: 100%;
}

.text-80 {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}
</style>
