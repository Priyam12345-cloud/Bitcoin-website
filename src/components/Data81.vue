<template>
  <div :class="[`data-763`, className || ``]">
    <div class="price-37 valign-text-middle taviraj-normal-white-14px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data81",
  props: ["children", "className"],
};
</script>

<style>
.data-763 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 46.43px;
  position: relative;
  width: 154.3px;
}

.price-37 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -10.14px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-763.data-764 {
  padding: 24px 10px 25px 45.61px;
}

.data-763.data-764 .price-37 {
  margin-right: -1.31px;
}

.data-763.data-765 {
  padding: 24px 10px 25px 45.39px;
}

.data-763.data-765 .price-37 {
  margin-right: -1.09px;
}

.data-763.data-766 {
  padding: 24px 10.01px 25px 45.09px;
}

.data-763.data-766 .price-37 {
  margin-right: -0.8px;
}

.data-763.data-767 {
  padding: 24px 10.01px 25px 46.62px;
}

.data-763.data-767 .price-37 {
  margin-right: -2.33px;
}

.data-763.data-768 {
  padding: 24px 10.01px 25px 46.81px;
}

.data-763.data-768 .price-37 {
  margin-right: -2.52px;
}
</style>
