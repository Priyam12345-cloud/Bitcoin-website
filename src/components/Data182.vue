<template>
  <div :class="[`data-436-1`, className || ``]">
    <container222 />
    <div class="percent-39 valign-text-middle taviraj-semi-bold-screamin-green-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data182",
  components: {
    Container222,
  },
  props: ["percent", "className"],
};
</script>

<style>
.data-436-1 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.37px;
  padding: 24px 10.01px 25px 16px;
  position: relative;
  width: 80.3px;
}

.percent-39 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-436-1.data-437,
.data-436-1.data-437-1 {
  gap: 4.38px;
}

.data-436-1.data-437-1 .percent-39 {
  margin-right: -1.84px;
}

.data-436-1.data-438 {
  gap: 4.38px;
  padding: 24px 10px 25px 16px;
}
</style>
