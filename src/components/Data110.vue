<template>
  <div :class="[`data-887`, className || ``]">
    <div class="x4847-m-11 valign-text-middle taviraj-semi-bold-white-17px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data110",
  props: ["children", "className"],
};
</script>

<style>
.data-887 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 50.12px;
  position: relative;
  width: 154.3px;
}

.x4847-m-11 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-887.data-888 {
  padding: 24px 10px 25px 50.17px;
}

.data-887.data-889 {
  padding: 24px 10px 25px 49.47px;
}

.data-887.data-890 {
  padding: 24px 10.01px 25px 49.43px;
}
</style>
