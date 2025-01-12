<template>
  <div :class="[`container-502`, className || ``]">
    <div class="container-503">
      <container62 :className="container62Props.className" />
      <div class="percent-12 valign-text-middle taviraj-semi-bold-screamin-green-20px">155.3%</div>
    </div>
  </div>
</template>

<script>
import Container62 from "./Container62";
export default {
  name: "Container822",
  components: {
    Container62,
  },
  props: ["className", "container62Props"],
};
</script>

<style>
.container-502 {
  align-items: center;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: flex-end;
  margin-right: -9.01px;
  max-width: 200.33px;
  padding: 1.5px 0px 2px;
  position: relative;
}

.container-503 {
  align-items: center;
  display: flex;
  gap: 4.4px;
  justify-content: flex-end;
  max-width: 105.92px;
  position: relative;
  width: 66px;
}

.percent-12 {
  letter-spacing: 0;
  line-height: 20px;
  margin-left: -8px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.container-502.container-504 {
  margin-right: -7.35px;
}
</style>
