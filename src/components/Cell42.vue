<template>
  <div :class="[`cell-101`, className || ``]">
    <div class="x1h-6 valign-text-middle taviraj-semi-bold-white-lilac-16px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Cell42",
  props: ["children", "className"],
};
</script>

<style>
.cell-101 {
  align-items: flex-start;
  background-color: var(--black);
  border-bottom-style: solid;
  border-bottom-width: 1px;
  display: flex;
  flex-direction: column;
  height: 40.5px;
  justify-content: center;
  margin-left: -1.84px;
  padding: 11.5px 57.01px 13px 62.48px;
  position: relative;
  width: 131.91px;
}

.x1h-6 {
  letter-spacing: 0;
  line-height: 16px;
  margin-right: -8.58px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.cell-101.cell-102 {
  border-left-style: solid;
  border-left-width: 1px;
  margin-left: unset;
  padding: 11.5px 55.94px 13px 61.92px;
  width: 131.66px;
}

.cell-101.cell-102 .x1h-6 {
  margin-right: -7.2px;
}
</style>
