<template>
  <div :class="[`data-372`, className || ``]">
    <container222 :className="container22Props.className" />
    <div class="percent-28 valign-text-middle taviraj-semi-bold-red-orange-15px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data622",
  components: {
    Container222,
  },
  props: ["percent", "className", "container22Props"],
};
</script>

<style>
.data-372 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10px 25px 16px;
  position: relative;
  width: 83.05px;
}

.percent-28 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-372.data-368,
.data-372.data-368-1,
.data-372.data-375 {
  height: unset;
}

.data-372.data-373,
.data-372.data-376 {
  height: unset;
  padding: 24px 10.01px 25px 16px;
}

.data-372.data-370,
.data-372.data-371 {
  gap: 4.38px;
  height: unset;
}

.data-372.data-368 .percent-28 {
  margin-right: -2.07px;
}
</style>
