<template>
  <div :class="[`container-397-1`, className || ``]">
    <div class="text valign-text-middle taviraj-semi-bold-white-14-4px">▾</div>
  </div>
</template>

<script>
export default {
  name: "Container3",
  props: ["className"],
};
</script>

<style>
.container-397-1 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 0.5px 0px;
  position: relative;
}

.text {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.container-397-1.container-404,
.container-397-1.container-405,
.container-397-1.container-406 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  margin-top: -0.5px;
  padding: 0.5px 0px;
  position: relative;
}
</style>
