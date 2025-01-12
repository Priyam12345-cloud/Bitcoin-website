<template>
  <div :class="[`cell-67`, className || ``]">
    <div class="last-7-days-2 valign-text-middle taviraj-semi-bold-white-12px">Last 7 Days</div>
  </div>
</template>

<script>
export default {
  name: "Cell11",
  props: ["className"],
};
</script>

<style>
.cell-67 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 41.5px;
  justify-content: center;
  margin-left: -2px;
  margin-right: -82.34px;
  padding: 12.5px 8px 13px 90.21px;
  position: relative;
  width: 164.69px;
}

.last-7-days-2 {
  letter-spacing: 0;
  line-height: 16px;
  margin-right: -2.52px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.cell-67.cell-69 {
  margin-right: unset;
}
</style>
