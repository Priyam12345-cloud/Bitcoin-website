<template>
  <div :class="[`data-857`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-68 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data103",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-857 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10px 25px 25.53px;
  position: relative;
  width: 83.05px;
}

.percent-68 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -0.61px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-857.data-858 {
  padding: 24px 10px 25px 25.61px;
}

.data-857.data-858 .percent-68 {
  margin-right: -0.69px;
}

.data-857.data-859 {
  gap: 4.37px;
  padding: 24px 10px 25px 25.85px;
}

.data-857.data-859 .percent-68 {
  margin-right: -0.92px;
}

.data-857.data-854,
.data-857.data-854-1 {
  gap: 4.37px;
  padding: 24px 10px 25px 25.41px;
}

.data-857.data-854-1 .percent-68,
.data-857.data-854 .percent-68 {
  margin-right: -0.48px;
}

.data-857.data-855,
.data-857.data-855-1,
.data-857.data-855-2,
.data-857.data-855-3 {
  padding: 24px 10px 25px 25.47px;
}

.data-857.data-855-1 .percent-68,
.data-857.data-855-2 .percent-68,
.data-857.data-855-3 .percent-68,
.data-857.data-855 .percent-68 {
  margin-right: -0.55px;
}

.data-857.data-860 {
  gap: 4.37px;
  padding: 24px 10.01px 25px 25.44px;
}

.data-857.data-860 .percent-68 {
  margin-right: -0.52px;
}

.data-857.data-856,
.data-857.data-856-1 {
  padding: 24px 10px 25px 25.58px;
}

.data-857.data-856-1 .percent-68,
.data-857.data-856 .percent-68 {
  margin-right: -0.66px;
}
</style>
