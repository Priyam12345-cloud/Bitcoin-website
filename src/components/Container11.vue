<template>
  <div :class="[`container-685-1`, className || ``]">
    <p class="lets-compare-how-bi valign-text-middle taviraj-medium-white-14px">{{ children }}</p>
  </div>
</template>

<script>
export default {
  name: "Container11",
  props: ["children", "className"],
};
</script>

<style>
.container-685-1 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 8px 0px 0px;
  position: relative;
  width: 100%;
}

.lets-compare-how-bi {
  align-self: stretch;
  letter-spacing: 0;
  line-height: 18.5px;
  margin-top: -1px;
  position: relative;
}

.container-685-1.container-686 {
  align-items: flex-start;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 8.01px 0px 0px;
  position: relative;
  width: 100%;
}
</style>
