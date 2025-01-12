<template>
  <div :class="[`iconfilluser`, className || ``]">
    <img
      class="vector-14"
      src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777a4880cdd8fda588782fc/img/vector-28@2x.png"
      alt="Vector"
    />
  </div>
</template>

<script>
export default {
  name: "Iconfilluser",
  props: ["className"],
};
</script>

<style>
.iconfilluser {
  height: 40px;
  position: relative;
  width: 40px;
}

.vector-14 {
  height: 35px;
  left: 6px;
  position: absolute;
  top: 2px;
  width: 27px;
}

.iconfilluser.iconfilluser-6 {
  margin-top: -11px;
}

.iconfilluser.iconfilluser-8,
.iconfilluser.iconfilluser-9,
.iconfilluser.iconfilluser-11,
.iconfilluser.iconfilluser-13 {
  margin-top: -5px;
}
</style>
