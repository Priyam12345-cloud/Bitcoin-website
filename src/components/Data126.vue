<template>
  <div :class="[`data-935`, className || ``]">
    <div class="price-55 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data126",
  props: ["children", "className"],
};
</script>

<style>
.data-935 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 61.81px;
  position: relative;
  width: 154.3px;
}

.price-55 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -0.52px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-935.data-936 {
  padding: 24px 10px 25px 61.83px;
}

.data-935.data-936 .price-55 {
  margin-right: -2.53px;
}

.data-935.data-937 {
  padding: 24px 10.01px 25px 62.31px;
}

.data-935.data-937 .price-55 {
  margin-right: -2.02px;
}
</style>
