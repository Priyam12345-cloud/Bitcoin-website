<template>
  <div :class="[`data-39-1`, className || ``]">
    <div class="data-40">
      <div class="address-6 valign-text-middle taviraj-semi-bold-white-20px">{{ children }}</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Data5",
  props: ["children", "className"],
};
</script>

<style>
.data-39-1 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 7px 10px 12px;
  position: relative;
  width: 164.69px;
}

.data-40 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 73px;
  margin-bottom: -23px;
  margin-right: -18.31px;
  padding: 17px 10.01px 25px 0px;
  position: relative;
  width: 163px;
}

.address-6 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-39-1.data-39 .data-40,
.data-39-1.data-41 .data-40 {
  padding: 18px 10.01px 25px 0px;
}
</style>
