<template>
  <div :class="[`data-416`, className || ``]">
    <container222 />
    <div class="percent-35 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data1522",
  components: {
    Container222,
  },
  props: ["percent", "className"],
};
</script>

<style>
.data-416 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.38px;
  padding: 24px 10.01px 25px 16px;
  position: relative;
  width: 80.3px;
}

.percent-35 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-416.data-417 {
  gap: 4.37px;
}

.data-416.data-418 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.38px;
  padding: 24px 10px 25px 16px;
  position: relative;
  width: 80.3px;
}
</style>
