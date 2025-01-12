<template>
  <div :class="[`data-863`, className || ``]">
    <div class="x4847-m-9 valign-text-middle taviraj-semi-bold-white-17px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data105",
  props: ["children", "className"],
};
</script>

<style>
.data-863 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 39.95px;
  position: relative;
  width: 154.3px;
}

.x4847-m-9 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-863.data-864 {
  padding: 24px 10px 25px 39.14px;
}

.data-863.data-865 {
  padding: 24px 10.01px 25px 40.9px;
}

.data-863.data-866 {
  padding: 24px 10.01px 25px 40.06px;
}

.data-863.data-867 {
  padding: 24px 10.01px 25px 40.18px;
}
</style>
