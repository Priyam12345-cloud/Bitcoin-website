<template>
  <div class="container-506">
    <div class="container-507">
      <container62 :className="container62Props.className" />
      <div class="percent-14 valign-text-middle taviraj-semi-bold-screamin-green-20px">95.2%</div>
    </div>
  </div>
</template>

<script>
import Container62 from "./Container62";
export default {
  name: "Container92",
  components: {
    Container62,
  },
  props: ["container62Props"],
};
</script>

<style>
.container-506,
.container-508 {
  align-items: center;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: flex-end;
  max-width: 200.33px;
  padding: 1.5px 0px 2px;
  position: relative;
}

.container-507,
.container-509 {
  align-items: center;
  display: flex;
  gap: 4.4px;
  justify-content: flex-end;
  max-width: 124.31px;
  position: relative;
  width: 70px;
}

.percent-14,
.percent-15 {
  letter-spacing: 0;
  line-height: 20px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
