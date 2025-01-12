<template>
  <div :class="[`data-832`, className || ``]">
    <div class="price-50 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data95",
  props: ["children", "className"],
};
</script>

<style>
.data-832 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 59.72px;
  position: relative;
  width: 111.17px;
}

.price-50 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -1.55px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-832.data-833 {
  padding: 24px 10px 25px 61px;
}

.data-832.data-833 .price-50 {
  margin-right: -1.83px;
}
</style>
