<template>
  <div class="cell-61">
    <container3 :className="container3Props.className" />
    <div class="x24h-volume-2 valign-text-middle taviraj-semi-bold-white-12px">24h Volume</div>
  </div>
</template>

<script>
import Container3 from "./Container3";
export default {
  name: "Cell9",
  components: {
    Container3,
  },
  props: ["container3Props"],
};
</script>

<style>
.cell-61,
.cell-62,
.cell-63 {
  align-items: flex-end;
  background-color: var(--black);
  display: flex;
  gap: 3px;
  height: 41px;
  margin-left: -2px;
  padding: 11.5px 7.01px 13px 62.23px;
  position: relative;
  width: 165px;
}

.x24h-volume-2,
.x24h-volume-3,
.x24h-volume-4 {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -0.5px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
