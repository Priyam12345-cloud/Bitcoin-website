<template>
  <div :class="[`data-212`, className || ``]">
    <div class="x156-b-1 valign-text-middle taviraj-semi-bold-white-17px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data292",
  props: ["children", "className"],
};
</script>

<style>
.data-212 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  left: 1089px;
  padding: 24px 10px 25px 70px;
  position: absolute;
  top: 1143px;
  width: 154px;
}

.x156-b-1 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-212.data-213 {
  left: unset;
  padding: 24px 10.01px 25px 69.09px;
  position: relative;
  top: unset;
  width: 154.3px;
}

.data-212.data-214 {
  left: unset;
  padding: 24px 10.01px 25px 69.98px;
  position: relative;
  top: unset;
  width: 154.3px;
}
</style>
