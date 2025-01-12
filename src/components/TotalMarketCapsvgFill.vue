<template>
  <div :class="[`x-64`, className || ``]">
    <img
      class="component-4-11"
      src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777a4880cdd8fda588782fc/img/component-4-165@2x.png"
      alt="Component 4"
    />
  </div>
</template>

<script>
export default {
  name: "TotalMarketCapsvgFill",
  props: ["className"],
};
</script>

<style>
.x-64 {
  align-items: center;
  display: flex;
  flex-direction: column;
  height: 58px;
  justify-content: center;
  left: 66px;
  padding: 0px 0px;
  position: absolute;
  top: 285px;
  width: 157px;
}

.component-4-11 {
  height: 58px;
  position: relative;
  width: 156.59px;
}

.x-64.total,
.x-64.total-1 {
  left: unset;
  position: relative;
  top: unset;
  width: 156.59px;
}

.x-64.total-1 .component-4-11,
.x-64.total .component-4-11 {
  height: 58px;
  width: 156.59px;
}

.x-64.total_market_capsvg-fill {
  left: 55px;
  top: 268px;
}

.x-64.total_market_capsvg-fill .component-4-11 {
  width: 156.59px;
}

.x-64.total_market_capsvg-fill-1,
.x-64.total_market_capsvg-fill-2 {
  align-self: center;
  left: unset;
  margin-bottom: 16px;
  position: relative;
  top: unset;
}
</style>
