<template>
  <div :class="[`data-789`, className || ``]">
    <div class="price-42 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data86",
  props: ["children", "className"],
};
</script>

<style>
.data-789 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 49.8px;
  position: relative;
  width: 154.3px;
}

.price-42 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -0.5px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-789.data-790 {
  padding: 24px 10px 25px 50.47px;
}

.data-789.data-790 .price-42 {
  margin-right: -0.17px;
}

.data-789.data-791 {
  padding: 24px 10px 25px 50.3px;
}

.data-789.data-791 .price-42 {
  margin-right: -1px;
}

.data-789.data-792 {
  padding: 24px 10.01px 25px 50.62px;
}

.data-789.data-792 .price-42 {
  margin-right: -0.33px;
}

.data-789.data-793 {
  padding: 24px 10px 25px 50.8px;
}

.data-789.data-794 {
  padding: 24px 10px 25px 50.72px;
}

.data-789.data-794 .price-42 {
  margin-right: -0.42px;
}
</style>
