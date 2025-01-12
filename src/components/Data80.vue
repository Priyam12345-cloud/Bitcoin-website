<template>
  <div :class="[`data-761`, className || ``]">
    <div class="price-36 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data80",
  props: ["children", "className"],
};
</script>

<style>
.data-761 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 58px;
  position: relative;
  width: 111.17px;
}

.price-36 {
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

.data-761.data-762 {
  padding: 24px 10px 25px 57.97px;
}

.data-761.data-762 .price-36 {
  margin-right: -0.8px;
}
</style>
