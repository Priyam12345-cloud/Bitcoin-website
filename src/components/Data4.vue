<template>
  <div :class="[`data-31-1`, className || ``]">
    <div class="number-4 valign-text-middle taviraj-semi-bold-lemon-16px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data4",
  props: ["children", "className"],
};
</script>

<style>
.data-31-1 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  padding: 24px 10.01px 25px 30px;
  position: relative;
  width: 154.3px;
}

.number-4 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-31-1.data-32,
.data-31-1.data-35 {
  padding: 24px 10px 25px 30px;
}

.data-31-1.data-37,
.data-31-1.data-38 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  opacity: 0.8;
  padding: 24px 10.01px 25px 30px;
  position: relative;
  width: 154.3px;
}

.data-31-1.data-33,
.data-31-1.data-36 {
  height: 69px;
}
</style>
