<template>
  <div class="container-668">
    <div class="symbol-1 valign-text-middle fontawesome5brands-regular-normal-white-12px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Container9",
  props: ["children"],
};
</script>

<style>
.container-668 {
  align-items: flex-end;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.symbol-1 {
  letter-spacing: 0;
  line-height: 12px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
