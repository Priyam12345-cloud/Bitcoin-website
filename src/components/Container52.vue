<template>
  <div :class="[`container-495`, className || ``]">
    <container62 :className="container62Props.className" />
    <div class="percent-10 valign-text-middle taviraj-semi-bold-screamin-green-20px">{{ percent }}</div>
  </div>
</template>

<script>
import Container62 from "./Container62";
export default {
  name: "Container52",
  components: {
    Container62,
  },
  props: ["percent", "className", "container62Props"],
};
</script>

<style>
.container-495 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 4.4px;
  justify-content: flex-end;
  margin-left: -43.4px;
  max-width: 89.38px;
  position: relative;
}

.percent-10 {
  letter-spacing: 0;
  line-height: 20px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.container-495.container-496,
.container-495.container-498 {
  margin-left: unset;
}

.container-495.container-497 {
  margin-left: unset;
  max-width: 89.05px;
}

.container-495.container-499 {
  margin-bottom: -5.25px;
  margin-left: unset;
  margin-top: -5.25px;
  max-width: 89.05px;
}
</style>
