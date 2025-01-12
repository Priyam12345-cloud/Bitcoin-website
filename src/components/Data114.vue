<template>
  <div :class="[`data-900`, className || ``]">
    <div class="x4847-m-14 valign-text-middle taviraj-semi-bold-white-17px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data114",
  props: ["children", "className"],
};
</script>

<style>
.data-900 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 37.98px;
  position: relative;
  width: 154.3px;
}

.x4847-m-14 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-900.data-901 {
  padding: 24px 10.01px 25px 38.79px;
}
</style>
