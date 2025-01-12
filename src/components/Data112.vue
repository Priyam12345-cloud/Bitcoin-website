<template>
  <div :class="[`data-895`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-69 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data112",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-895 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10px 25px 29.52px;
  position: relative;
  width: 83.05px;
}

.percent-69 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -4.59px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-895.data-896 {
  gap: 4.38px;
  padding: 24px 10px 25px 29.17px;
}

.data-895.data-896 .percent-69 {
  margin-right: -4.25px;
}
</style>
