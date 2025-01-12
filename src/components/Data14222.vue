<template>
  <div :class="[`data-413-1`, className || ``]">
    <container222 />
    <div class="percent-34 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data14222",
  components: {
    Container222,
  },
  props: ["percent", "className"],
};
</script>

<style>
.data-413-1 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.37px;
  padding: 24px 10px 25px 16px;
  position: relative;
  width: 83.05px;
}

.percent-34 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-413-1.data-414 {
  gap: 4.38px;
}

.data-413-1.data-415 {
  padding: 24px 10.01px 25px 16px;
}
</style>
