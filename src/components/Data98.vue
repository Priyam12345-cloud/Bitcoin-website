<template>
  <div :class="[`data-843`, className || ``]">
    <div class="price-53 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data98",
  props: ["children", "className"],
};
</script>

<style>
.data-843 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 9.99px 25px 63.49px;
  position: relative;
  width: 111.17px;
}

.price-53 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -0.31px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-843.data-844 {
  padding: 24px 9.99px 25px 64.74px;
}

.data-843.data-844 .price-53 {
  margin-right: -0.56px;
}

.data-843.data-845 {
  padding: 24px 9.99px 25px 64.35px;
}

.data-843.data-845 .price-53 {
  margin-right: -0.17px;
}
</style>
