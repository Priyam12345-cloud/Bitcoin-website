<template>
  <div :class="[`data-324`, className || ``]">
    <div class="x156-b-5 valign-text-middle taviraj-semi-bold-white-17px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data302",
  props: ["children", "className"],
};
</script>

<style>
.data-324 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  left: 915px;
  padding: 24px 10.01px 25px 65px;
  position: absolute;
  top: 1909px;
  width: 154px;
}

.x156-b-5 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-324.data-325 {
  left: unset;
  padding: 24px 10px 25px 63px;
  position: relative;
  top: unset;
  width: 154.3px;
}

.data-324.data-326 {
  left: unset;
  padding: 24px 10.01px 25px 63.56px;
  position: relative;
  top: unset;
  width: 154.3px;
}
</style>
