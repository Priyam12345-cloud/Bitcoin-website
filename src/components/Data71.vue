<template>
  <div :class="[`data-718`, className || ``]">
    <div class="price-27 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data71",
  props: ["children", "className"],
};
</script>

<style>
.data-718 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 45.61px;
  position: relative;
  width: 111.17px;
}

.price-27 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -0.44px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-718.data-719 {
  padding: 24px 9.99px 25px 45.4px;
}

.data-718.data-719 .price-27 {
  margin-right: -1.22px;
}

.data-718.data-720 {
  padding: 24px 10px 25px 46.08px;
}

.data-718.data-720 .price-27 {
  margin-right: -0.91px;
}

.data-718.data-721 {
  padding: 24px 10px 25px 45.36px;
}

.data-718.data-721 .price-27 {
  margin-right: -0.19px;
}

.data-718.data-722 {
  padding: 24px 9.99px 25px 45.13px;
}

.data-718.data-722 .price-27 {
  margin-right: unset;
}

.data-718.data-723 {
  padding: 24px 9.99px 25px 45.3px;
}

.data-718.data-723 .price-27 {
  margin-right: -0.12px;
}
</style>
