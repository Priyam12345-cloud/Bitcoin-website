<template>
  <div :class="[`data-851`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-64 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data102",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-851 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10px 25px 25.37px;
  position: relative;
  width: 80.3px;
}

.percent-64 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -3.2px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-851.data-852 {
  gap: 4.37px;
  padding: 24px 10.01px 25px 25.42px;
}

.data-851.data-852 .percent-64 {
  margin-right: -3.25px;
}

.data-851.data-853 {
  padding: 24px 10.01px 25px 25.21px;
}

.data-851.data-853 .percent-64 {
  margin-right: -3.05px;
}
</style>
