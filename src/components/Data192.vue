<template>
  <div :class="[`data-439`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-40 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data192",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-439 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10px 25px 20.01px;
  position: relative;
  width: 74.97px;
}

.percent-40 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -3.17px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-439.data-442 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10.01px 25px 20.03px;
  position: relative;
  width: 74.97px;
}

.data-439.data-442 .percent-40 {
  margin-right: -3.19px;
}

.data-439.data-443 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10.01px 25px 21px;
  position: relative;
  width: 74.97px;
}

.data-439.data-443 .percent-40 {
  margin-right: -4.16px;
}

.data-439.data-440 {
  background-color: var(--black);
}

.data-439.data-444 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10px 25px 20.09px;
  position: relative;
  width: 74.97px;
}

.data-439.data-444 .percent-40 {
  margin-right: -3.25px;
}

.data-439.data-441,
.data-439.data-441-1 {
  background-color: var(--black);
  padding: 24px 10px 25px 20.04px;
}

.data-439.data-441-1 .percent-40,
.data-439.data-441 .percent-40 {
  margin-right: -3.2px;
}
</style>
