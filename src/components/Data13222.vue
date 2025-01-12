<template>
  <div class="data-412">
    <container222 />
    <div class="percent-33 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data13222",
  components: {
    Container222,
  },
  props: ["percent"],
};
</script>

<style>
.data-412 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10.01px 25px 12px;
  position: relative;
  width: 74.97px;
}

.percent-33 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
