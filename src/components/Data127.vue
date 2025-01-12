<template>
  <div :class="[`data-938`, className || ``]">
    <div class="price-57 valign-text-middle taviraj-normal-white-14px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data127",
  props: ["children", "className"],
};
</script>

<style>
.data-938 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 49.43px;
  position: relative;
  width: 154.3px;
}

.price-57 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -5.14px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-938.data-939 {
  padding: 24px 10.01px 25px 49.84px;
}

.data-938.data-939 .price-57 {
  margin-right: -5.55px;
}

.data-938.data-940 {
  padding: 24px 10.01px 25px 49.54px;
}

.data-938.data-940 .price-57 {
  margin-right: -5.25px;
}

.data-938.data-941 {
  padding: 24px 10.01px 25px 50.84px;
}

.data-938.data-941 .price-57,
.data-938.data-942 .price-57,
.data-938.data-943 .price-57 {
  margin-right: unset;
}

.data-938.data-942 {
  padding: 24px 10.01px 25px 50.34px;
}

.data-938.data-943 {
  padding: 24px 10.01px 25px 50.79px;
}
</style>
