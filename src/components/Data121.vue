<template>
  <div :class="[`data-921`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-74 valign-text-middle taviraj-semi-bold-screamin-green-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data121",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-921 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10px 25px 25.37px;
  position: relative;
  width: 80.3px;
}

.percent-74 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -3.2px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-921.data-922 {
  padding: 24px 10px 25px 25.15px;
}

.data-921.data-922 .percent-74 {
  margin-right: -2.98px;
}
</style>
