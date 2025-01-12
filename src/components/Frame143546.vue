<template>
  <div :class="[`frame-14354-8-1`, className || ``]">
    <div class="group-1191-3"></div>
    <div class="group-7-4">
      <div class="overlap-group-30">
        <div class="x1st-prize-2 valign-text-middle taviraj-semi-bold-white-27px">1st Prize :</div>
        <p class="address-57 valign-text-middle taviraj-bold-white-36px">{{ address }}</p>
      </div>
    </div>
    <img class="trophy-cup-3" :src="trophyCup" alt="Trophy Cup" /><group9
      :children="group9Props.children"
      :className="group9Props.className"
    />
  </div>
</template>

<script>
import Group9 from "./Group9";
export default {
  name: "Frame143546",
  components: {
    Group9,
  },
  props: ["address", "trophyCup", "className", "group9Props"],
};
</script>

<style>
.frame-14354-8-1 {
  align-items: center;
  display: flex;
  gap: 11px;
  height: 57px;
  padding: 2px 0px 0px;
  position: relative;
  width: 1065px;
}

.group-1191-3 {
  background-image: url(https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/icon-medal-3-gold-4@2x.png);
  background-size: 100% 100%;
  height: 79.57px;
  margin-bottom: -12.28px;
  margin-top: -12.28px;
  position: relative;
  width: 100px;
}

.group-7-4 {
  height: 57px;
  margin-bottom: -1px;
  margin-top: -1px;
  position: relative;
  width: 688px;
}

.overlap-group-30 {
  height: 57px;
  position: relative;
  width: 684px;
}

.x1st-prize-2 {
  height: 57px;
  left: 0;
  letter-spacing: 0;
  line-height: 32px;
  position: absolute;
  top: 0;
  width: 146px;
}

.address-57 {
  height: 54px;
  left: 128px;
  letter-spacing: 0;
  line-height: 32px;
  position: absolute;
  top: 3px;
  width: 556px;
}

.trophy-cup-3 {
  height: 71.75px;
  margin-bottom: -14.25px;
  margin-top: -2.5px;
  position: relative;
  width: 61.54px;
}

.frame-14354-8-1.frame-14354-8 .group-1191-3 {
  background-image: url(https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/icon-medal-3-gold-5@2x.png);
}

.frame-14354-8-1.frame-14354-8 .trophy-cup-3 {
  height: 71.75px;
}

.frame-14354-8-1.frame-14354-9-1 .group-1191-3,
.frame-14354-8-1.frame-14354-9 .group-1191-3 {
  background-image: url(https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/icon-medal-3-gold-8@2x.png);
  height: 79.57px;
}
</style>
