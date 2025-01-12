<template>
  <div :class="[`data-366`, className || ``]">
    <container222 :className="container22Props.className" />
    <div class="percent-26 valign-text-middle taviraj-semi-bold-red-orange-15px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data522",
  components: {
    Container222,
  },
  props: ["percent", "className", "container22Props"],
};
</script>

<style>
.data-366 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10.01px 25px 16px;
  position: relative;
  width: 80.3px;
}

.percent-26 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-366.data-364,
.data-366.data-369 {
  height: unset;
}

.data-366.data-367,
.data-366.data-365 {
  gap: 4.38px;
  height: unset;
}
</style>
