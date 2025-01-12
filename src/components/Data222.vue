<template>
  <div :class="[`data-451`, className || ``]">
    <container222 :className="container222Props.className" />
    <div class="percent-46 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data222",
  components: {
    Container222,
  },
  props: ["percent", "className", "container222Props"],
};
</script>

<style>
.data-451 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10px 25px 16.47px;
  position: relative;
  width: 74.97px;
}

.percent-46 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-451.data-449 {
  background-color: var(--black);
  padding: 24px 10.01px 25px 16.53px;
}

.data-451.data-450 {
  background-color: var(--black);
}

.data-451.data-452 {
  background-color: var(--black);
  padding: 24px 10.01px 25px 16.67px;
}
</style>
