<template>
  <div class="component-15-2">
    <div class="text-79 valign-text-middle taviraj-semi-bold-white-14px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Component15",
  props: ["children"],
};
</script>

<style>
.component-15-2 {
  align-items: flex-start;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.text-79 {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}
</style>
