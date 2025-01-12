<template>
  <div :class="[`cell-5`, className || ``]"><container3 /></div>
</template>

<script>
import Container3 from "./Container3";
export default {
  name: "Cell",
  components: {
    Container3,
  },
  props: ["className"],
};
</script>

<style>
.cell-5 {
  align-items: flex-end;
  background-color: var(--licorice);
  display: flex;
  gap: 3px;
  height: 42px;
  margin-bottom: -2px;
  margin-left: -2px;
  margin-top: -2px;
  padding: 11.5px 7.01px 13px 39.87px;
  position: relative;
  width: 79px;
}

.cell-5.cell-6,
.cell-5.cell-9 {
  margin-left: unset;
}

.cell-5.cell-7,
.cell-5.cell-8 {
  background-color: var(--black);
  margin-bottom: unset;
  margin-left: unset;
  margin-top: unset;
}
</style>
