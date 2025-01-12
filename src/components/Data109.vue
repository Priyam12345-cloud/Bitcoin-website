<template>
  <div :class="[`data-884`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-67 valign-text-middle taviraj-semi-bold-screamin-green-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data109",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-884 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10px 25px 25.61px;
  position: relative;
  width: 83.05px;
}

.percent-67 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -0.69px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-884.data-885 {
  padding: 24px 10px 25px 25.08px;
}

.data-884.data-885 .percent-67 {
  margin-right: -0.16px;
}

.data-884.data-886 {
  gap: 4.37px;
  padding: 24px 10px 25px 25.35px;
}

.data-884.data-886 .percent-67 {
  margin-right: -0.42px;
}
</style>
