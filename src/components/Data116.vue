<template>
  <div :class="[`data-907`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-71 valign-text-middle taviraj-semi-bold-screamin-green-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data116",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-907 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10px 25px 28.1px;
  position: relative;
  width: 83.05px;
}

.percent-71 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -3.17px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-907.data-908 {
  gap: 4.38px;
  padding: 24px 10px 25px 27.97px;
}

.data-907.data-908 .percent-71 {
  margin-right: -3.05px;
}
</style>
