<template>
  <div :class="[`data-359-1`, className || ``]">
    <container222 :className="container22Props.className" />
    <div class="percent-24 valign-text-middle taviraj-semi-bold-red-orange-15px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data472",
  components: {
    Container222,
  },
  props: ["percent", "className", "container22Props"],
};
</script>

<style>
.data-359-1 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10px 25px 12px;
  position: relative;
  width: 74.97px;
}

.percent-24 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-359-1.data-360,
.data-359-1.data-362 {
  gap: 4.37px;
  padding: 24px 10.01px 25px 12px;
}

.data-359-1.data-363 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10px 25px 12px;
  position: relative;
  width: 74.97px;
}
</style>
