<template>
  <div :class="[`data-881`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-66 valign-text-middle taviraj-semi-bold-screamin-green-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data108",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-881 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10.01px 25px 23.32px;
  position: relative;
  width: 80.3px;
}

.percent-66 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -1.16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-881.data-882 {
  padding: 24px 10px 25px 23.12px;
}

.data-881.data-882 .percent-66 {
  margin-right: -0.95px;
}

.data-881.data-883 {
  padding: 24px 10.01px 25px 23.18px;
}

.data-881.data-883 .percent-66 {
  margin-right: -1.02px;
}
</style>
