<template>
  <div :class="[`data-826`, className || ``]">
    <div class="price-48 valign-text-middle taviraj-normal-white-14px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data94",
  props: ["children", "className"],
};
</script>

<style>
.data-826 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10px 25px 40.92px;
  position: relative;
  width: 154.3px;
}

.price-48 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-826.data-827 {
  padding: 24px 10.01px 25px 40.43px;
}

.data-826.data-828 {
  padding: 24px 10.01px 25px 40.76px;
}

.data-826.data-829 {
  padding: 24px 10px 25px 40.25px;
}

.data-826.data-830 {
  padding: 24px 10.01px 25px 40.82px;
}

.data-826.data-831 {
  padding: 24px 10.01px 25px 40.87px;
}
</style>
