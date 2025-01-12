<template>
  <div :class="[`data-897`, className || ``]">
    <div class="x4847-m-13 valign-text-middle taviraj-semi-bold-white-17px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data113",
  props: ["children", "className"],
};
</script>

<style>
.data-897 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 53.45px;
  position: relative;
  width: 154.3px;
}

.x4847-m-13 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-897.data-898 {
  padding: 24px 10px 25px 54px;
}

.data-897.data-899 {
  padding: 24px 10px 25px 54.61px;
}
</style>
