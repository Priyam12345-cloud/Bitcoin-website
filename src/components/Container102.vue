<template>
  <div :class="[`container-510`, className || ``]">
    <container62 :className="container62Props.className" />
    <div class="percent-16 valign-text-middle taviraj-semi-bold-screamin-green-20px">69.7%</div>
  </div>
</template>

<script>
import Container62 from "./Container62";
export default {
  name: "Container102",
  components: {
    Container62,
  },
  props: ["className", "container62Props"],
};
</script>

<style>
.container-510 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 4.4px;
  justify-content: flex-end;
  max-width: 125.19px;
  position: relative;
}

.percent-16 {
  letter-spacing: 0;
  line-height: 20px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.container-510.container-511 {
  margin-bottom: -4.75px;
  margin-top: -4.75px;
}
</style>
