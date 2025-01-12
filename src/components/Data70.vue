<template>
  <div :class="[`data-713`, className || ``]">
    <div class="price-28 valign-text-middle taviraj-normal-white-14px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data70",
  props: ["children", "className"],
};
</script>

<style>
.data-713 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 36.31px;
  position: relative;
  width: 154.3px;
}

.price-28 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -9.02px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-713.data-714 {
  padding: 24px 10.01px 25px 35.82px;
}

.data-713.data-714 .price-28,
.data-713.data-715 .price-28 {
  margin-right: unset;
}

.data-713.data-715 {
  padding: 24px 10.01px 25px 36.01px;
}

.data-713.data-716 {
  padding: 24px 10.01px 25px 36.79px;
}

.data-713.data-716 .price-28 {
  margin-right: -0.5px;
}

.data-713.data-717 {
  padding: 24px 10.01px 25px 36.76px;
}

.data-713.data-717 .price-28 {
  margin-right: -0.47px;
}
</style>
