<template>
  <div :class="[`data-902`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-70 valign-text-middle taviraj-semi-bold-screamin-green-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data115",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-902 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10.01px 25px 22.57px;
  position: relative;
  width: 80.3px;
}

.percent-70 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -0.41px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-902.data-903 {
  padding: 24px 10px 25px 22.26px;
}

.data-902.data-903 .percent-70 {
  margin-right: -0.09px;
}

.data-902.data-904 {
  gap: 4.37px;
  padding: 24px 10.01px 25px 22.5px;
}

.data-902.data-904 .percent-70 {
  margin-right: -0.33px;
}

.data-902.data-905 {
  padding: 24px 10.01px 25px 22.32px;
}

.data-902.data-905 .percent-70 {
  margin-right: -0.16px;
}

.data-902.data-906 {
  padding: 24px 10.01px 25px 22.43px;
}

.data-902.data-906 .percent-70 {
  margin-right: -0.27px;
}
</style>
