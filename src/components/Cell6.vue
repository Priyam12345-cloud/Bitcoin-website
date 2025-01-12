<template>
  <div class="cell-52">
    <container3 />
    <div class="x1h-2 valign-text-middle taviraj-semi-bold-white-12px">1h</div>
  </div>
</template>

<script>
import Container3 from "./Container3";
export default {
  name: "Cell6",
  components: {
    Container3,
  },
};
</script>

<style>
.cell-52,
.cell-53,
.cell-54 {
  align-items: flex-end;
  background-color: var(--black);
  display: flex;
  gap: 3px;
  height: 41.5px;
  margin-left: -2px;
  padding: 11.5px 7.01px 13px 39.87px;
  position: relative;
  width: 74.97px;
}

.x1h-2,
.x1h-3,
.x1h-4 {
  letter-spacing: 0;
  line-height: 16px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
