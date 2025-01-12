<template>
  <div :class="[`data-782`, className || ``]">
    <div class="price-40 valign-text-middle taviraj-normal-white-14px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data84",
  props: ["children", "className"],
};
</script>

<style>
.data-782 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 32.17px;
  position: relative;
  width: 154.3px;
}

.price-40 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-782.data-783 {
  padding: 24px 10px 25px 31.67px;
}
</style>
