<template>
  <div :class="[`frame-14350-2`, className || ``]">
    <frame14348 :address="frame14348Props.address" />
    <div class="frame-14349-8">
      <div class="entry-2 valign-text-middle taviraj-semi-bold-white-32px">Entry</div>
      <frame14361 />
    </div>
  </div>
</template>

<script>
import Frame14348 from "./Frame14348";
import Frame14361 from "./Frame14361";
export default {
  name: "Frame143502",
  components: {
    Frame14348,
    Frame14361,
  },
  props: ["className", "frame14348Props"],
};
</script>

<style>
.frame-14350-2 {
  align-items: center;
  align-self: stretch;
  display: flex;
  gap: 696px;
  height: 5px;
  padding: 5px 44px 5px 76px;
  position: relative;
  width: 100%;
}

.frame-14349-8 {
  align-items: flex-end;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 12px;
  justify-content: flex-end;
  margin-bottom: -47.5px;
  margin-right: -6px;
  margin-top: -47.5px;
  position: relative;
}

.entry-2 {
  height: 40px;
  letter-spacing: 0;
  line-height: 32px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  width: 102px;
}

.frame-14350-2.frame-14350-3 {
  margin-top: -11px;
}
</style>
