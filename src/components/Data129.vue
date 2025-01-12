<template>
  <div :class="[`data-945`, className || ``]">
    <div class="price-56 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data129",
  props: ["children", "className"],
};
</script>

<style>
.data-945 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 67.55px;
  position: relative;
  width: 154.3px;
}

.price-56 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -2.25px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-945.data-946 {
  padding: 24px 10px 25px 67.53px;
}

.data-945.data-946 .price-56 {
  margin-right: -2.23px;
}
</style>
