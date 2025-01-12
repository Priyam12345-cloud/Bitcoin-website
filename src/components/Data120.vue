<template>
  <div :class="[`data-918`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-75 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data120",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-918 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10px 25px 24.96px;
  position: relative;
  width: 83.05px;
}

.percent-75 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -0.03px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-918.data-919 {
  padding: 24px 10px 25px 24.77px;
}

.data-918.data-919 .percent-75,
.data-918.data-920 .percent-75 {
  margin-right: unset;
}

.data-918.data-920 {
  padding: 24px 10px 25px 24.52px;
}
</style>
