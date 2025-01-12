<template>
  <div :class="[`frame-14350-4`, className || ``]">
    <frame14348 :address="frame14348Props.address" :className="frame14348Props.className" />
    <div class="frame-14349-10">
      <div class="entry-4 valign-text-middle taviraj-semi-bold-white-32px">Entry</div>
      <frame14361 :className="frame14361Props.className" />
    </div>
  </div>
</template>

<script>
import Frame14348 from "./Frame14348";
import Frame14361 from "./Frame14361";
export default {
  name: "Frame143503",
  components: {
    Frame14348,
    Frame14361,
  },
  props: ["className", "frame14348Props", "frame14361Props"],
};
</script>

<style>
.frame-14350-4 {
  align-items: center;
  align-self: stretch;
  display: flex;
  gap: 696px;
  height: 5px;
  padding: 5px 44px 5px 76px;
  position: relative;
  width: 100%;
}

.frame-14349-10 {
  align-items: flex-end;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 12px;
  justify-content: flex-end;
  margin-bottom: -47px;
  margin-right: -6px;
  margin-top: -47px;
  position: relative;
}

.entry-4 {
  height: 38px;
  letter-spacing: 0;
  line-height: 32px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: 102px;
}

.frame-14350-4.frame-14350-5 {
  margin-top: -11px;
}
</style>
