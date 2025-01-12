<template>
  <div class="heading-3-6">
    <div class="x-bitcoin valign-text-middle taviraj-semi-bold-lemon-20px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Heading3",
  props: ["children"],
};
</script>

<style>
.heading-3-6 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 20px 0px 0px;
  position: relative;
  width: 100%;
}

.x-bitcoin {
  align-self: stretch;
  letter-spacing: 0;
  line-height: 24px;
  margin-top: -1px;
  position: relative;
}
</style>
