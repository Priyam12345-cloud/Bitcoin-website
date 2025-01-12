<template>
  <div :class="[`data-981`, className || ``]">
    <div class="text-33-1 valign-text-middle taviraj-semi-bold-white-14px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data252",
  props: ["children", "className"],
};
</script>

<style>
.data-981 {
  align-items: center;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 1.75px;
  justify-content: flex-end;
  padding: 0.5px 2.75px 1.5px 8px;
  position: relative;
}

.text-33-1 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-981.data-982 {
  align-items: flex-end;
  flex-direction: column;
  gap: unset;
  justify-content: unset;
  padding: 1px 1px 1px 8px;
}
</style>
