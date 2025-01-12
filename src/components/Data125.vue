<template>
  <div :class="[`data-933`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-76 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data125",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-933 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10px 25px 26.28px;
  position: relative;
  width: 83.05px;
}

.percent-76 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -1.36px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-933.data-934 {
  gap: 4.37px;
  padding: 24px 10px 25px 26.27px;
}

.data-933.data-934 .percent-76 {
  margin-right: -9.34px;
}
</style>
