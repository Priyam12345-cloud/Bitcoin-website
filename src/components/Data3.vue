<template>
  <div :class="[`data-25-1`, className || ``]">
    <div class="address-4 valign-text-middle taviraj-semi-bold-white-17px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data3",
  props: ["children", "className"],
};
</script>

<style>
.data-25-1 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 15px;
  position: relative;
  width: 154.3px;
}

.address-4 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-25-1.data-26,
.data-25-1.data-30 {
  padding: 24px 10.01px 25px 15px;
}
</style>
