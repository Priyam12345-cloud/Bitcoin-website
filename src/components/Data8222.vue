<template>
  <div :class="[`data-455`, className || ``]">
    <div class="text-99 valign-text-middle taviraj-semi-bold-white-17px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data8222",
  props: ["children", "className"],
};
</script>

<style>
.data-455 {
  align-items: flex-start;
  background-color: var(--ebony);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22px 9.99px 25px 0px;
  position: relative;
  width: 111.17px;
}

.text-99 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-455.data-456 {
  padding: 21px 10px 25px 0px;
}
</style>
