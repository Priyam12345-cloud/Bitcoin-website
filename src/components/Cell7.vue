<template>
  <div class="cell-55">
    <container3 />
    <div class="x24h-2 valign-text-middle taviraj-semi-bold-white-12px">24h</div>
  </div>
</template>

<script>
import Container3 from "./Container3";
export default {
  name: "Cell7",
  components: {
    Container3,
  },
};
</script>

<style>
.cell-55,
.cell-56,
.cell-57 {
  align-items: flex-end;
  background-color: var(--black);
  display: flex;
  gap: 3px;
  height: 41.5px;
  margin-left: -2px;
  padding: 11.5px 7px 13px 35px;
  position: relative;
  width: 80.3px;
}

.x24h-2,
.x24h-3,
.x24h-4 {
  letter-spacing: 0;
  line-height: 16px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
