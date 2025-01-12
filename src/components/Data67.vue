<template>
  <div :class="[`data-701`, className || ``]">
    <div class="price-24 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data67",
  props: ["children", "className"],
};
</script>

<style>
.data-701 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 34.75px;
  position: relative;
  width: 111.17px;
}

.price-24 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-701.data-702 {
  padding: 24px 9.99px 25px 33.65px;
}

.data-701.data-703 {
  padding: 24px 9.99px 25px 33.04px;
}
</style>
