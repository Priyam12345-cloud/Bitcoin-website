<template>
  <div :class="[`paragraph-61`, className || ``]">
    <div class="usdc-1 valign-text-middle taviraj-semi-bold-white-lilac-15px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Paragraph5",
  props: ["children", "className"],
};
</script>

<style>
.paragraph-61 {
  display: flex;
  height: 20px;
  position: relative;
  width: 77.48px;
}

.usdc-1 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -0.5px;
  white-space: nowrap;
  width: 43.71px;
}

.paragraph-61.paragraph-62 {
  width: 77.84px;
}

.paragraph-61.paragraph-62 .usdc-1 {
  margin-left: -0.1px;
  margin-top: -1px;
  width: 66px;
}
</style>
