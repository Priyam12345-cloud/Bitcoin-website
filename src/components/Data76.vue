<template>
  <div :class="[`data-746`, className || ``]">
    <div class="price-33 valign-text-middle taviraj-normal-white-14px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data76",
  props: ["children", "className"],
};
</script>

<style>
.data-746 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 33.01px;
  position: relative;
  width: 154.3px;
}

.price-33 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-746.data-747 {
  padding: 24px 10.01px 25px 34.9px;
}

.data-746.data-748 {
  padding: 24px 10.01px 25px 33.07px;
}
</style>
