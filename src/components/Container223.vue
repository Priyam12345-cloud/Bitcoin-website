<template>
  <div :class="[`container-535`, className || ``]">
    <div class="text-102 valign-text-middle taviraj-bold-white-20px">▴</div>
  </div>
</template>

<script>
export default {
  name: "Container223",
  props: ["className"],
};
</script>

<style>
.container-535 {
  align-items: flex-start;
  display: flex;
  height: 19px;
  justify-content: center;
  margin-top: -4.5px;
  padding: 0.5px 0px;
  position: relative;
  width: 8px;
}

.text-102 {
  height: 18px;
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  white-space: nowrap;
  width: 8px;
}

.container-535.container-536 {
  margin-top: -3px;
}
</style>
