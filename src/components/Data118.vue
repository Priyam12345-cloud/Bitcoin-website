<template>
  <div :class="[`data-914`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-72 valign-text-middle taviraj-semi-bold-screamin-green-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data118",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-914 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10.01px 25px 26.42px;
  position: relative;
  width: 80.3px;
}

.percent-72 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -4.25px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-914.data-915 {
  gap: 4.38px;
  padding: 24px 10.01px 25px 26.68px;
}

.data-914.data-915 .percent-72 {
  margin-right: -4.52px;
}

.data-914.data-916 {
  padding: 24px 10.01px 25px 26.56px;
}

.data-914.data-916 .percent-72 {
  margin-right: -4.39px;
}
</style>
