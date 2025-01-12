<template>
  <div :class="[`data-87`, className || ``]">
    <div class="number-8 valign-text-middle taviraj-semi-bold-lemon-15px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data492",
  props: ["children", "className"],
};
</script>

<style>
.data-87 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  justify-content: center;
  left: 145px;
  padding: 24px 10px 25px;
  position: absolute;
  top: 1144px;
  width: 75px;
}

.number-8 {
  height: 25px;
  letter-spacing: 0;
  line-height: 20px;
  margin-bottom: -1.5px;
  margin-top: -3.5px;
  position: relative;
  width: 10px;
}

.data-87.data-88 {
  top: 1525px;
}

.data-87.data-89 {
  left: 143px;
  top: 1912px;
}

.data-87.data-89 .number-8 {
  width: 20px;
}

.data-87.data-90 {
  left: 146px;
  padding: 25px 10px;
  top: -502px;
}

.data-87.data-90 .number-8 {
  margin-bottom: -2px;
  margin-top: -4px;
}
</style>
