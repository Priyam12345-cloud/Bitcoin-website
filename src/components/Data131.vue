<template>
  <div :class="[`data-949`, className || ``]">
    <div class="price-60 valign-text-middle taviraj-normal-white-14px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data131",
  props: ["children", "className"],
};
</script>

<style>
.data-949 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 53.07px;
  position: relative;
  width: 154.3px;
}

.price-60 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -8.78px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-949.data-950 {
  padding: 24px 10.01px 25px 53.96px;
}

.data-949.data-950 .price-60,
.data-949.data-951 .price-60,
.data-949.data-952 .price-60 {
  margin-right: unset;
}

.data-949.data-951 {
  padding: 24px 10.01px 25px 54.23px;
}

.data-949.data-952 {
  padding: 24px 10.01px 25px 53.12px;
}
</style>
