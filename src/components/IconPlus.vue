<template>
  <div :class="[`icon-plus`, className || ``]">
    <div class="overlap-group">
      <img
        class="rectangle-1"
        src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/rectangle-1.svg"
        alt="Rectangle 1"
      />
      <img
        class="rectangle-2-1"
        src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/rectangle-2-1.svg"
        alt="Rectangle 2"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "IconPlus",
  props: ["className"],
};
</script>

<style>
.icon-plus {
  align-items: center;
  background-image: url(https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/ellipse-1-4.svg);
  background-size: 100% 100%;
  display: flex;
  height: 50px;
  left: 803px;
  min-width: 50px;
  padding: 0 12px;
  position: absolute;
  top: 753px;
}

.overlap-group {
  height: 26px;
  position: relative;
  width: 26px;
}

.rectangle-1 {
  height: 4px;
  left: 0;
  position: absolute;
  top: 11px;
  width: 26px;
}

.rectangle-2-1 {
  height: 26px;
  left: 11px;
  position: absolute;
  top: 0;
  width: 4px;
}

.icon-plus.icon-plus-1,
.icon-plus.icon-plus-7 {
  left: 1054px;
  top: 754px;
}

.icon-plus.icon-plus-2,
.icon-plus.icon-plus-8 {
  left: 540px;
  top: 1138px;
}

.icon-plus.icon-plus-3,
.icon-plus.icon-plus-9 {
  left: 810px;
  top: 1143px;
}

.icon-plus.icon-plus-4,
.icon-plus.icon-plus-10 {
  left: 1075px;
  top: 1135px;
}

.icon-plus.icon-plus-5,
.icon-plus.icon-plus-11 {
  left: 1349px;
  top: 1135px;
}
</style>
