<template>
  <div :class="[`data-169`, className || ``]">
    <container62 />
    <div class="percent-7 valign-text-middle taviraj-semi-bold-red-orange-16px">{{ percent }}</div>
  </div>
</template>

<script>
import Container62 from "./Container62";
export default {
  name: "Data510",
  components: {
    Container62,
  },
  props: ["percent", "className"],
};
</script>

<style>
.data-169 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.37px;
  height: 69px;
  left: 745px;
  padding: 24px 10.01px 25px 22.56px;
  position: absolute;
  top: 1143px;
  width: 80px;
}

.percent-7 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -7.64px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-169.data-170 {
  left: 744px;
  top: 1236px;
}

.data-169.data-171 {
  left: 743px;
  top: 1325px;
}

.data-169.data-172 {
  left: 743px;
  top: 1419px;
}

.data-169.data-173 {
  left: 744px;
  top: 1525px;
}
</style>
