<template>
  <div :class="[`data-849-1`, className || ``]">
    <div class="text-73 valign-text-middle taviraj-semi-bold-white-17px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data101",
  props: ["children", "className"],
};
</script>

<style>
.data-849-1 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 25px 25px 10px;
  position: relative;
  width: 111.17px;
}

.text-73 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-849-1.data-849-2 .text-73,
.data-849-1.data-849-3 .text-73 {
  margin-right: -6.83px;
}

.data-849-1.data-849-4 .text-73 {
  margin-right: -2.83px;
}

.data-849-1.data-850 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 36px 25px 10px;
  position: relative;
  width: 111.17px;
}

.data-849-1.data-850 .text-73 {
  margin-right: -13.83px;
}

.data-849-1.data-849-5 .text-73,
.data-849-1.data-849 .text-73 {
  margin-right: -21.83px;
}
</style>
