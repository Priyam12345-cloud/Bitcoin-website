<template>
  <div :class="[`data-433`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-37 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data172",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-433 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10.01px 25px 19.31px;
  position: relative;
  width: 74.97px;
}

.percent-37 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -2.47px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-433.data-434 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10.01px 25px 19.78px;
  position: relative;
  width: 74.97px;
}

.data-433.data-434 .percent-37 {
  margin-right: -2.94px;
}

.data-433.data-435 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10px 25px 19.82px;
  position: relative;
  width: 74.97px;
}

.data-433.data-435 .percent-37 {
  margin-right: -2.98px;
}
</style>
