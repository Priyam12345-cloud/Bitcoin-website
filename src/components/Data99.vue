<template>
  <div :class="[`data-846`, className || ``]">
    <div class="price-54 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data99",
  props: ["children", "className"],
};
</script>

<style>
.data-846 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 9.99px 25px 68.02px;
  position: relative;
  width: 111.17px;
}

.price-54 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -1.84px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-846.data-847 {
  padding: 24px 9.99px 25px 67.99px;
}

.data-846.data-847 .price-54 {
  margin-right: -1.81px;
}
</style>
