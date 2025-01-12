<template>
  <div :class="[`imgmargin-2`, className || ``]">
    <div class="firstfigitaljpeg" :style="{ 'background-image': 'url(' + src + ')' }"></div>
  </div>
</template>

<script>
export default {
  name: "Imgmargin",
  props: ["src", "className"],
};
</script>

<style>
.imgmargin-2 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  height: 24px;
  max-width: 312.05px;
  padding: 0px 8px 0px 0px;
  position: relative;
  width: 32px;
}

.firstfigitaljpeg {
  background-position: 50% 50%;
  background-size: cover;
  height: 24px;
  max-width: 304.05px;
  position: relative;
  width: 24px;
}

.imgmargin-2.imgmargin-5 .firstfigitaljpeg {
  max-width: unset;
}
</style>
