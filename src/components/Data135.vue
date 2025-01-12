<template>
  <div :class="[`data-968`, className || ``]">
    <div class="price-63 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data135",
  props: ["children", "className"],
};
</script>

<style>
.data-968 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 9.99px 25px 39.46px;
  position: relative;
  width: 111.17px;
}

.price-63 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -1.28px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-968.data-969 {
  padding: 24px 9.99px 25px 39.77px;
}

.data-968.data-969 .price-63 {
  margin-right: -0.59px;
}

.data-968.data-970 {
  padding: 24px 9.99px 25px 39.63px;
}

.data-968.data-970 .price-63 {
  margin-right: -1.45px;
}
</style>
