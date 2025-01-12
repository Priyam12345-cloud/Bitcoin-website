<template>
  <div class="heading-2-4">
    <div class="btc-21 valign-text-middle taviraj-bold-white-18px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Heading2",
  props: ["children"],
};
</script>

<style>
.heading-2-4 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
  width: 100%;
}

.btc-21 {
  align-self: stretch;
  letter-spacing: 0;
  line-height: 28px;
  margin-top: -1px;
  position: relative;
}
</style>
