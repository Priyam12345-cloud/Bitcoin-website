<template>
  <div :class="[`data-732`, className || ``]">
    <div class="price-30 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data73",
  props: ["children", "className"],
};
</script>

<style>
.data-732 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 49px;
  position: relative;
  width: 111.17px;
}

.price-30 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -0.83px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-732.data-733 {
  padding: 24px 10px 25px 48.86px;
}

.data-732.data-733 .price-30 {
  margin-right: -1.69px;
}

.data-732.data-734 {
  padding: 24px 9.99px 25px 48.07px;
}

.data-732.data-734 .price-30 {
  margin-right: -0.89px;
}

.data-732.data-735 {
  padding: 24px 9.99px 25px 48.66px;
}

.data-732.data-735 .price-30 {
  margin-right: -0.48px;
}

.data-732.data-736 {
  padding: 24px 9.99px 25px 48.55px;
}

.data-732.data-736 .price-30 {
  margin-right: -1.37px;
}

.data-732.data-737 {
  padding: 24px 9.99px 25px 48.9px;
}

.data-732.data-737 .price-30 {
  margin-right: -0.72px;
}

.data-732.data-738 {
  padding: 24px 9.99px 25px 47.85px;
}

.data-732.data-738 .price-30 {
  margin-right: -0.67px;
}
</style>
