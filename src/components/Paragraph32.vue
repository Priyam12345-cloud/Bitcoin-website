<template>
  <div :class="[`paragraph-60`, className || ``]">
    <div class="solana-1 valign-text-middle taviraj-semi-bold-white-lilac-15px">{{ solana }}</div>
    <div class="sol valign-text-middle taviraj-bold-lemon-11px">{{ sol }}</div>
  </div>
</template>

<script>
export default {
  name: "Paragraph32",
  props: ["solana", "sol", "className"],
};
</script>

<style>
.paragraph-60 {
  display: flex;
  gap: 6px;
  height: 20px;
  position: relative;
  width: 91px;
}

.solana-1 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: -0.2px;
  margin-top: -0.2px;
  white-space: nowrap;
  width: 61px;
}

.sol {
  height: 16px;
  letter-spacing: 0;
  line-height: 16px;
  margin-top: 1.8px;
  white-space: nowrap;
  width: 35px;
}

.paragraph-60.paragraph-59,
.paragraph-60.paragraph-59-1 {
  display: unset;
  gap: unset;
}

.paragraph-60.paragraph-59-1 .solana-1,
.paragraph-60.paragraph-59 .solana-1 {
  left: 0;
  margin-left: unset;
  margin-top: unset;
  position: absolute;
  top: -1px;
}

.paragraph-60.paragraph-59-1 .sol,
.paragraph-60.paragraph-59 .sol {
  left: 67px;
  margin-top: unset;
  position: absolute;
  top: 1px;
}
</style>
