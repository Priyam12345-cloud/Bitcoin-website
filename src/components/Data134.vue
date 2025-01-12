<template>
  <div :class="[`data-964`, className || ``]">
    <div class="price-62 valign-text-middle taviraj-normal-white-14px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data134",
  props: ["children", "className"],
};
</script>

<style>
.data-964 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 24px 10.01px 25px 55.45px;
  position: relative;
  width: 154.3px;
}

.price-62 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -0.16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.data-964.data-965 {
  padding: 24px 10.01px 25px 56.56px;
}

.data-964.data-965 .price-62 {
  margin-right: -1.27px;
}

.data-964.data-966 {
  padding: 24px 10px 25px 56.14px;
}

.data-964.data-966 .price-62 {
  margin-right: -0.84px;
}

.data-964.data-967 {
  padding: 24px 10px 25px 56.25px;
}

.data-964.data-967 .price-62 {
  margin-right: -0.95px;
}
</style>
