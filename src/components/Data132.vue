<template>
  <div :class="[`data-953`, className || ``]">
    <div class="price-59 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data132",
  props: ["children", "className"],
};
</script>

<style>
.data-953 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 65.87px;
  position: relative;
  width: 154.3px;
}

.price-59 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -1.58px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-953.data-954 {
  padding: 24px 10.01px 25px 65.98px;
}

.data-953.data-954 .price-59 {
  margin-right: -1.69px;
}
</style>
