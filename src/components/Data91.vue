<template>
  <div :class="[`data-812`, className || ``]">
    <div class="price-46 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data91",
  props: ["children", "className"],
};
</script>

<style>
.data-812 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 9.99px 25px 27.9px;
  position: relative;
  width: 111.17px;
}

.price-46 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -0.72px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-812.data-813 {
  padding: 24px 9.99px 25px 28.04px;
}

.data-812.data-813 .price-46 {
  margin-right: -1.86px;
}

.data-812.data-814 {
  padding: 24px 10px 25px 27.5px;
}

.data-812.data-814 .price-46 {
  margin-right: -0.33px;
}
</style>
