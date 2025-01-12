<template>
  <div :class="[`data-741`, className || ``]">
    <div class="price-32 valign-text-middle wwwcoingeckocomsemanticinput">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data75",
  props: ["children", "className"],
};
</script>

<style>
.data-741 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 59.39px;
  position: relative;
  width: 154.3px;
}

.price-32 {
  color: var(--dhancowhite);
  font-weight: 400;
  line-height: 20px;
  margin-right: -1.09px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-741.data-742 {
  padding: 24px 10px 25px 60.25px;
}

.data-741.data-742 .price-32 {
  margin-right: -2.95px;
}

.data-741.data-743 {
  padding: 24px 10px 25px 59.42px;
}

.data-741.data-743 .price-32 {
  margin-right: -1.12px;
}

.data-741.data-744 {
  padding: 24px 10px 25px 59.36px;
}

.data-741.data-744 .price-32 {
  margin-right: -0.06px;
}

.data-741.data-745 {
  padding: 24px 10.01px 25px 59.62px;
}

.data-741.data-745 .price-32 {
  margin-right: -0.33px;
}
</style>
