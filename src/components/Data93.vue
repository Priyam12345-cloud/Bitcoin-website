<template>
  <div :class="[`data-822`, className || ``]">
    <div class="price-49 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data93",
  props: ["children", "className"],
};
</script>

<style>
.data-822 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 32.22px;
  position: relative;
  width: 111.17px;
}

.price-49 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -0.05px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-822.data-823 {
  padding: 24px 9.99px 25px 32.21px;
}

.data-822.data-823 .price-49 {
  margin-right: -0.03px;
}

.data-822.data-824 {
  padding: 24px 10px 25px 32.58px;
}

.data-822.data-824 .price-49,
.data-822.data-825 .price-49 {
  margin-right: unset;
}

.data-822.data-825 {
  padding: 24px 10px 25px 32.75px;
}
</style>
