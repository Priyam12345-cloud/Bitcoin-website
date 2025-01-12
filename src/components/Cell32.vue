<template>
  <div :class="[`cell-19`, className || ``]">
    <container3223 :className="container32Props.className" />
    <div class="x7d-1 valign-text-middle taviraj-semi-bold-white-23px">7d</div>
  </div>
</template>

<script>
import Container3223 from "./Container3223";
export default {
  name: "Cell32",
  components: {
    Container3223,
  },
  props: ["className", "container32Props"],
};
</script>

<style>
.cell-19 {
  align-items: flex-end;
  background-color: var(--ebony);
  display: flex;
  height: 42px;
  padding: 11.5px 20px 15px 42px;
  position: relative;
  width: 70px;
}

.x7d-1 {
  height: 27px;
  letter-spacing: 0;
  line-height: 16px;
  margin-left: -29px;
  margin-right: -21px;
  margin-top: -12.5px;
  position: relative;
  text-align: right;
  width: 29px;
}

.cell-19.cell-20 {
  left: 731px;
  position: absolute;
  top: 551px;
}
</style>
