<template>
  <div :class="[`cell-43`, className || ``]">
    <div class="container-558"><div class="text-162 valign-text-middle taviraj-semi-bold-white-14-4px-2">▴</div></div>
    <div class="text-163 valign-text-middle taviraj-semi-bold-white-12px">#</div>
  </div>
</template>

<script>
export default {
  name: "Cell3",
  props: ["className"],
};
</script>

<style>
.cell-43 {
  align-items: flex-end;
  background-color: var(--black);
  display: flex;
  gap: 3px;
  height: 41.5px;
  margin-left: -49px;
  padding: 11.5px 4px 13px 10px;
  position: relative;
  width: 49.38px;
}

.container-558 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 0.5px 0px;
  position: relative;
}

.text-162 {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.text-163 {
  letter-spacing: 0;
  line-height: 16px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.cell-43.cell-45 {
  margin-left: -2px;
}
</style>
