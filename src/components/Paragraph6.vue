<template>
  <div :class="[`paragraph-65-1`, className || ``]">
    <div class="name-4 valign-text-middle taviraj-semi-bold-white-lilac-16px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Paragraph6",
  props: ["children", "className"],
};
</script>

<style>
.paragraph-65-1 {
  display: flex;
  height: 20px;
  position: relative;
  width: 154.13px;
}

.name-4 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -0.5px;
  white-space: nowrap;
  width: 113.47px;
}

.paragraph-65-1.paragraph-67 .name-4 {
  margin-left: -0.1px;
  margin-top: 0;
  transform: rotate(-0.09deg);
  width: 147.51px;
}
</style>
