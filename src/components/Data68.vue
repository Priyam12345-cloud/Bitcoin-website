<template>
  <div :class="[`data-704`, className || ``]">
    <div class="price-25 valign-text-middle taviraj-normal-white-14px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data68",
  props: ["children", "className"],
};
</script>

<style>
.data-704 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 27.39px;
  position: relative;
  width: 154.3px;
}

.price-25 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -0.09px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-704.data-705 {
  padding: 24px 10.01px 25px 27.82px;
}

.data-704.data-705 .price-25 {
  margin-right: unset;
}
</style>
