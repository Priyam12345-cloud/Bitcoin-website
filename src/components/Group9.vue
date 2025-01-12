<template>
  <div :class="[`group-9-2`, className || ``]">
    <div class="winners-6 valign-text-middle taviraj-semi-bold-white-27px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Group9",
  props: ["children", "className"],
};
</script>

<style>
.group-9-2 {
  display: flex;
  height: 19px;
  position: relative;
  width: 223px;
}

.winners-6 {
  height: 19px;
  letter-spacing: 0;
  line-height: 32px;
  white-space: nowrap;
  width: 221px;
}

.group-9-2.group-9,
.group-9-2.group-9-1 {
  margin-right: -15px;
}
</style>
