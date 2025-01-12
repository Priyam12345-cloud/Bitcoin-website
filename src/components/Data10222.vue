<template>
  <div :class="[`data-398`, className || ``]"><link-sparklinesvg /></div>
</template>

<script>
import LinkSparklinesvg from "./LinkSparklinesvg";
export default {
  name: "Data10222",
  components: {
    LinkSparklinesvg,
  },
  props: ["className"],
};
</script>

<style>
.data-398 {
  align-items: flex-start;
  background-color: var(--ebony);
  display: flex;
  flex-direction: column;
  height: 69px;
  margin-right: -0.01px;
  padding: 7px 10px 12px 19.69px;
  position: relative;
  width: 164.69px;
}

.data-398.data-401,
.data-398.data-402 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 7px 10px 12px 19.69px;
  position: relative;
  width: 164.69px;
}

.data-398.data-400 {
  background-color: var(--black);
  margin-right: -7.01px;
}
</style>
