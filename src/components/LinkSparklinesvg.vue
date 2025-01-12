<template>
  <div :class="[`link-sparklinesvg-1-1`, className || ``]">
    <div class="sparklinesvg-fill-2">
      <img
        class="component-4-1"
        src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/677524890cdd8fda58877d13/img/component-4@2x.png"
        alt="Component 4"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "LinkSparklinesvg",
  props: ["className"],
};
</script>

<style>
.link-sparklinesvg-1-1 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  max-width: 1270px;
  position: relative;
}

.sparklinesvg-fill-2 {
  align-items: center;
  display: flex;
  flex-direction: column;
  height: 50px;
  justify-content: center;
  position: relative;
  width: 135px;
}

.component-4-1 {
  height: 50px;
  position: relative;
  width: 135px;
}

.link-sparklinesvg-1-1.link-sparklinesvg-6 {
  margin-right: -19.69px;
}

.link-sparklinesvg-1-1.link-sparklinesvg-7,
.link-sparklinesvg-1-1.link-sparklinesvg-10 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  margin-bottom: -3px;
  max-width: 1270px;
  position: relative;
}
</style>
