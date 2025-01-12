<template>
  <div :class="[`data-403-1`, className || ``]">
    <container222 :className="container22Props.className" />
    <div class="percent-30 valign-text-middle taviraj-normal-screamin-green-15px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data11222",
  components: {
    Container222,
  },
  props: ["percent", "className", "container22Props"],
};
</script>

<style>
.data-403-1 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.38px;
  padding: 24px 10.01px 25px 16px;
  position: relative;
  width: 80.3px;
}

.percent-30 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-403-1.data-404 {
  gap: 4.37px;
}
</style>
