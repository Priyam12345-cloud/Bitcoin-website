<template>
  <div :class="[`data-947`, className || ``]">
    <div class="price-58 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data130",
  props: ["children", "className"],
};
</script>

<style>
.data-947 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 71.84px;
  position: relative;
  width: 154.3px;
}

.price-58 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -0.55px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-947.data-948 {
  padding: 24px 10px 25px 71.78px;
}

.data-947.data-948 .price-58 {
  margin-right: -1.48px;
}
</style>
