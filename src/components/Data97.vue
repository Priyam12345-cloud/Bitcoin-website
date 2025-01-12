<template>
  <div :class="[`data-840`, className || ``]">
    <div class="price-52 valign-text-middle taviraj-normal-white-14px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data97",
  props: ["children", "className"],
};
</script>

<style>
.data-840 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 47.37px;
  position: relative;
  width: 154.3px;
}

.price-52 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -3.08px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-840.data-841 {
  padding: 24px 10.01px 25px 47.2px;
}

.data-840.data-841 .price-52 {
  margin-right: -2.91px;
}

.data-840.data-842 {
  padding: 24px 10px 25px 47.53px;
}

.data-840.data-842 .price-52 {
  margin-right: -3.23px;
}
</style>
