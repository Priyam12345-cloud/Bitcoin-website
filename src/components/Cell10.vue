<template>
  <div class="cell-64">
    <container3 />
    <div class="market-cap-3 valign-text-middle taviraj-semi-bold-white-12px">Market Cap</div>
  </div>
</template>

<script>
import Container3 from "./Container3";
export default {
  name: "Cell10",
  components: {
    Container3,
  },
};
</script>

<style>
.cell-64,
.cell-65,
.cell-66 {
  align-items: flex-end;
  background-color: var(--black);
  display: flex;
  gap: 3px;
  height: 41.5px;
  margin-left: -2px;
  padding: 11.5px 7.01px 13px 64.57px;
  position: relative;
  width: 154.3px;
}

.market-cap-3,
.market-cap-4,
.market-cap-5 {
  letter-spacing: 0;
  line-height: 16px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
