<template>
  <div :class="[`data-868`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-65 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data106",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-868 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10px 25px 22.37px;
  position: relative;
  width: 80.3px;
}

.percent-65 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -0.2px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-868.data-871 {
  padding: 24px 10.01px 25px 22.57px;
}

.data-868.data-871 .percent-65 {
  margin-right: -0.41px;
}

.data-868.data-869,
.data-868.data-869-1,
.data-868.data-869-2 {
  gap: 4.37px;
  padding: 24px 10.01px 25px 22.59px;
}

.data-868.data-869-1 .percent-65,
.data-868.data-869-2 .percent-65,
.data-868.data-869 .percent-65 {
  margin-right: -0.42px;
}

.data-868.data-872 {
  gap: 4.37px;
  padding: 24px 10.01px 25px 22.5px;
}

.data-868.data-872 .percent-65 {
  margin-right: -0.33px;
}

.data-868.data-870,
.data-868.data-870-1 {
  padding: 24px 10.01px 25px 22.32px;
}

.data-868.data-870-1 .percent-65,
.data-868.data-870 .percent-65 {
  margin-right: -0.16px;
}

.data-868.data-873 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10.01px 25px 22.78px;
  position: relative;
  width: 80.3px;
}

.data-868.data-873 .percent-65 {
  margin-right: -0.61px;
}
</style>
