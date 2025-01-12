<template>
  <div class="data-445">
    <container222 />
    <div class="percent-42 valign-text-middle taviraj-semi-bold-red-orange-14px">{{ percent }}</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data202",
  components: {
    Container222,
  },
  props: ["percent"],
};
</script>

<style>
.data-445 {
  align-items: center;
  background-color: var(--ebony);
  display: flex;
  gap: 4.38px;
  height: 69px;
  padding: 24px 10px 25px 21.09px;
  position: relative;
  width: 74.97px;
}

.percent-42 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -4.25px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
