<template>
  <div :class="[`data-446`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-43 valign-text-middle taviraj-semi-bold-screamin-green-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data212",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-446 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.37px;
  padding: 24px 10px 25px 16px;
  position: relative;
  width: 83.05px;
}

.percent-43 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-446.data-447 {
  gap: 4.38px;
}

.data-446.data-448 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10.01px 25px 16.69px;
  position: relative;
  width: 83.05px;
}
</style>
