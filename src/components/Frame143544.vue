<template>
  <div class="frame-14354-6">
    <div class="group-1191"></div>
    <div class="group-7-2">
      <div class="overlap-group-28">
        <div class="x1st-prize valign-text-middle taviraj-semi-bold-white-27px">1st Prize :</div>
        <p class="address-53 valign-text-middle taviraj-bold-white-36px">&nbsp;&nbsp;&nbsp;&nbsp;25 Lakh</p>
      </div>
    </div>
    <img
      class="trophy-cup"
      src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/trophy-cup-2@2x.png"
      alt="Trophy Cup"
    />
    <group9 :children="group9Props.children" />
  </div>
</template>

<script>
import Group9 from "./Group9";
export default {
  name: "Frame143544",
  components: {
    Group9,
  },
  props: ["group9Props"],
};
</script>

<style>
.frame-14354-6,
.frame-14354-7 {
  align-items: center;
  display: flex;
  flex: 0 0 auto;
  gap: 11px;
  padding: 2px 0px 0px;
  position: relative;
  width: 1065px;
}

.group-1191,
.group-1191-1 {
  background-image: url(https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/icon-medal-3-gold-3@2x.png);
  background-size: 100% 100%;
  height: 79.57px;
  position: relative;
  width: 100px;
}

.group-7-2,
.group-7-3 {
  height: 57px;
  position: relative;
  width: 673px;
}

.overlap-group-28,
.overlap-group-29 {
  height: 57px;
  position: relative;
  width: 669px;
}

.x1st-prize,
.x1st-prize-1 {
  height: 57px;
  left: 0;
  letter-spacing: 0;
  line-height: 32px;
  position: absolute;
  top: 0;
  width: 143px;
}

.address-53,
.address-54 {
  height: 54px;
  left: 132px;
  letter-spacing: 0;
  line-height: 32px;
  position: absolute;
  top: 2px;
  width: 537px;
}

.trophy-cup,
.trophy-cup-1 {
  height: 71.75px;
  margin-bottom: -1.97px;
  position: relative;
  width: 61.54px;
}
</style>
