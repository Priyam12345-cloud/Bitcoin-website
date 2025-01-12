<template>
  <div :class="[`paragraph-31-1`, className || ``]">
    <div class="bitget-token valign-text-middle inter-semi-bold-white-lilac-17px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Paragraph22",
  props: ["children", "className"],
};
</script>

<style>
.paragraph-31-1 {
  display: flex;
  height: 20px;
  position: relative;
  width: 112.64px;
}

.bitget-token {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: -0.3px;
  margin-top: -0.5px;
  white-space: nowrap;
  width: 113px;
}

.paragraph-31-1.paragraph-31-2 .bitget-token,
.paragraph-31-1.paragraph-31-3 .bitget-token,
.paragraph-31-1.paragraph-32-2 .bitget-token,
.paragraph-31-1.paragraph-32-3 .bitget-token {
  margin-left: unset;
  width: 88.25px;
}

.paragraph-31-1.paragraph-31 .bitget-token,
.paragraph-31-1.paragraph-32 .bitget-token {
  width: 97px;
}
</style>
