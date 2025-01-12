<template>
  <div :class="[`data-21-1`, className || ``]">
    <div class="number-10 valign-text-middle taviraj-semi-bold-lemon-15px">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Data2",
  props: ["children", "className"],
};
</script>

<style>
.data-21-1 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  justify-content: center;
  padding: 24px 10px 25px 0px;
  position: relative;
  width: 49.38px;
}

.number-10 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  width: 37px;
}

.data-21-1.data-21-2 .number-10,
.data-21-1.data-24-2 .number-10,
.data-21-1.data-21-3 .number-10,
.data-21-1.data-21-4 .number-10,
.data-21-1.data-21-5 .number-10,
.data-21-1.data-21-6 .number-10,
.data-21-1.data-21-7 .number-10,
.data-21-1.data-21-8 .number-10,
.data-21-1.data-24-3 .number-10,
.data-21-1.data-24-4 .number-10,
.data-21-1.data-24-5 .number-10,
.data-21-1.data-24-6 .number-10,
.data-21-1.data-24-7 .number-10,
.data-21-1.data-24-8 .number-10 {
  width: 21px;
}

.data-21-1.data-21-9 .number-10,
.data-21-1.data-24-9 .number-10,
.data-21-1.data-21-10 .number-10,
.data-21-1.data-21-11 .number-10,
.data-21-1.data-21-12 .number-10,
.data-21-1.data-21-13 .number-10,
.data-21-1.data-21-14 .number-10,
.data-21-1.data-21-15 .number-10,
.data-21-1.data-21-16 .number-10,
.data-21-1.data-21-17 .number-10,
.data-21-1.data-21-18 .number-10,
.data-21-1.data-21-19 .number-10,
.data-21-1.data-21-20 .number-10,
.data-21-1.data-21-21 .number-10,
.data-21-1.data-21-22 .number-10,
.data-21-1.data-21-23 .number-10,
.data-21-1.data-21-24 .number-10,
.data-21-1.data-21-25 .number-10,
.data-21-1.data-21-26 .number-10,
.data-21-1.data-21-27 .number-10,
.data-21-1.data-21-28 .number-10,
.data-21-1.data-21 .number-10,
.data-21-1.data-24-10 .number-10,
.data-21-1.data-24-11 .number-10,
.data-21-1.data-24-12 .number-10,
.data-21-1.data-24-13 .number-10,
.data-21-1.data-24-14 .number-10,
.data-21-1.data-24-15 .number-10,
.data-21-1.data-24-16 .number-10,
.data-21-1.data-24-17 .number-10,
.data-21-1.data-24-18 .number-10,
.data-21-1.data-24-19 .number-10,
.data-21-1.data-24-20 .number-10,
.data-21-1.data-24-21 .number-10,
.data-21-1.data-24-22 .number-10,
.data-21-1.data-24-23 .number-10,
.data-21-1.data-24-24 .number-10,
.data-21-1.data-24-25 .number-10,
.data-21-1.data-24-26 .number-10,
.data-21-1.data-24-27 .number-10,
.data-21-1.data-24-28 .number-10,
.data-21-1.data-24 .number-10 {
  width: 39px;
}

.data-21-1.data-22-1 .number-10,
.data-21-1.data-23-1 .number-10,
.data-21-1.data-22-2 .number-10,
.data-21-1.data-22-3 .number-10,
.data-21-1.data-22-4 .number-10,
.data-21-1.data-22-5 .number-10,
.data-21-1.data-22-6 .number-10,
.data-21-1.data-22-7 .number-10,
.data-21-1.data-22-8 .number-10,
.data-21-1.data-22-9 .number-10,
.data-21-1.data-22-10 .number-10,
.data-21-1.data-22-11 .number-10,
.data-21-1.data-22-12 .number-10,
.data-21-1.data-22-13 .number-10,
.data-21-1.data-22-14 .number-10,
.data-21-1.data-22-15 .number-10,
.data-21-1.data-22-16 .number-10,
.data-21-1.data-22-17 .number-10,
.data-21-1.data-22-18 .number-10,
.data-21-1.data-22-19 .number-10,
.data-21-1.data-22-20 .number-10,
.data-21-1.data-22-21 .number-10,
.data-21-1.data-22-22 .number-10,
.data-21-1.data-22-23 .number-10,
.data-21-1.data-22-24 .number-10,
.data-21-1.data-22-25 .number-10,
.data-21-1.data-22-26 .number-10,
.data-21-1.data-22-27 .number-10,
.data-21-1.data-22-28 .number-10,
.data-21-1.data-22-29 .number-10,
.data-21-1.data-22-30 .number-10,
.data-21-1.data-22-31 .number-10,
.data-21-1.data-22-32 .number-10,
.data-21-1.data-22-33 .number-10,
.data-21-1.data-22-34 .number-10,
.data-21-1.data-22-35 .number-10,
.data-21-1.data-22-36 .number-10,
.data-21-1.data-22-37 .number-10,
.data-21-1.data-22-38 .number-10,
.data-21-1.data-22-39 .number-10,
.data-21-1.data-22-40 .number-10,
.data-21-1.data-22-41 .number-10,
.data-21-1.data-22-42 .number-10,
.data-21-1.data-22-43 .number-10,
.data-21-1.data-22 .number-10,
.data-21-1.data-23-2 .number-10,
.data-21-1.data-23-3 .number-10,
.data-21-1.data-23-4 .number-10,
.data-21-1.data-23-5 .number-10,
.data-21-1.data-23-6 .number-10,
.data-21-1.data-23-7 .number-10,
.data-21-1.data-23-8 .number-10,
.data-21-1.data-23-9 .number-10,
.data-21-1.data-23-10 .number-10,
.data-21-1.data-23-11 .number-10,
.data-21-1.data-23-12 .number-10,
.data-21-1.data-23-13 .number-10,
.data-21-1.data-23-14 .number-10,
.data-21-1.data-23-15 .number-10,
.data-21-1.data-23-16 .number-10,
.data-21-1.data-23-17 .number-10,
.data-21-1.data-23-18 .number-10,
.data-21-1.data-23-19 .number-10,
.data-21-1.data-23-20 .number-10,
.data-21-1.data-23-21 .number-10,
.data-21-1.data-23-22 .number-10,
.data-21-1.data-23-23 .number-10,
.data-21-1.data-23-24 .number-10,
.data-21-1.data-23-25 .number-10,
.data-21-1.data-23-26 .number-10,
.data-21-1.data-23-27 .number-10,
.data-21-1.data-23-28 .number-10,
.data-21-1.data-23-29 .number-10,
.data-21-1.data-23-30 .number-10,
.data-21-1.data-23-31 .number-10,
.data-21-1.data-23-32 .number-10,
.data-21-1.data-23-33 .number-10,
.data-21-1.data-23-34 .number-10,
.data-21-1.data-23-35 .number-10,
.data-21-1.data-23-36 .number-10,
.data-21-1.data-23-37 .number-10,
.data-21-1.data-23-38 .number-10,
.data-21-1.data-23-39 .number-10,
.data-21-1.data-23-40 .number-10,
.data-21-1.data-23-41 .number-10,
.data-21-1.data-23-42 .number-10,
.data-21-1.data-23-43 .number-10,
.data-21-1.data-23 .number-10 {
  width: 33px;
}
</style>
