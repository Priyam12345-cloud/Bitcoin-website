<template>
  <div :class="[`paragraph-27`, className || ``]">
    <div class="white-bit-coin valign-text-middle taviraj-semi-bold-white-lilac-17px">WhiteBIT Coin</div>
  </div>
</template>

<script>
export default {
  name: "Paragraph2",
  props: ["className"],
};
</script>

<style>
.paragraph-27 {
  display: flex;
  height: 20px;
  position: relative;
  width: 127.16px;
}

.white-bit-coin {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: -0.3px;
  margin-top: -0.5px;
  white-space: nowrap;
  width: 127px;
}

.paragraph-27.paragraph-30 .white-bit-coin {
  margin-left: -0.1px;
  margin-top: -1px;
}
</style>
