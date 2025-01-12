<template>
  <div class="cell-49">
    <container3 />
    <div class="place-53 valign-text-middle taviraj-semi-bold-white-12px">Price</div>
  </div>
</template>

<script>
import Container3 from "./Container3";
export default {
  name: "Cell5",
  components: {
    Container3,
  },
};
</script>

<style>
.cell-49,
.cell-50,
.cell-51 {
  align-items: flex-end;
  background-color: var(--black);
  display: flex;
  gap: 3px;
  height: 41.5px;
  margin-left: -2px;
  padding: 11.5px 6.99px 13px 58.66px;
  position: relative;
  width: 111.17px;
}

.place-53,
.place-54,
.place-55 {
  letter-spacing: 0;
  line-height: 16px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
