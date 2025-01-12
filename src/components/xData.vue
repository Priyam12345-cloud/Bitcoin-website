<template>
  <div :class="[`data-979`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-84 valign-text-middle taviraj-normal-screamin-green-15px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "xData",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-979 {
  align-items: center;
  display: flex;
  gap: 4.06px;
  height: 39.02px;
  margin-left: -1.84px;
  padding: 10.24px 42.05px 10.26px 45.61px;
  position: relative;
  width: 131.91px;
}

.percent-84 {
  letter-spacing: 0;
  line-height: 18.5px;
  margin-right: -2.93px;
  margin-top: -1.24px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}

.data-979.data-980 {
  border-color: var(--black);
  border-left-style: solid;
  border-left-width: 1px;
  gap: 4.05px;
  margin-left: unset;
  padding: 10.24px 41.99px 10.26px 46.05px;
  width: 131.66px;
}

.data-979.data-980 .percent-84 {
  margin-right: -3.55px;
}
</style>
