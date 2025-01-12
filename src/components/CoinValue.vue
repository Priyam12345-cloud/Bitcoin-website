<template>
  <div :class="[`coin-value-2-1`, className || ``]">
    <div class="frame-108-2">
      <div class="x5662354-2 taviraj-semi-bold-white-24px">{{ x5662354 }}</div>
      <p class="x141-1 taviraj-medium-screamin-green-18px">{{ x141 }}</p>
    </div>
    <img class="chart-state-1-2" :src="chartState1" alt="chart-state 1" />
  </div>
</template>

<script>
export default {
  name: "CoinValue",
  props: ["x5662354", "x141", "chartState1", "className"],
};
</script>

<style>
.coin-value-2-1 {
  align-items: center;
  display: flex;
  flex: 0 0 auto;
  justify-content: space-between;
  position: relative;
  width: 252px;
}

.frame-108-2 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  gap: 9px;
  justify-content: center;
  position: relative;
  width: 140px;
}

.x5662354-2 {
  align-self: stretch;
  letter-spacing: 0;
  line-height: normal;
  margin-top: -1px;
  position: relative;
}

.x141-1 {
  align-self: stretch;
  letter-spacing: 0;
  line-height: 28.8px;
  position: relative;
}

.chart-state-1-2 {
  height: 53.27px;
  object-fit: cover;
  position: relative;
  width: 100px;
}

.coin-value-2-1.coin-value-2-3 .chart-state-1-2,
.coin-value-2-1.coin-value-2-4 .chart-state-1-2,
.coin-value-2-1.coin-value-2 .chart-state-1-2 {
  height: 53.27px;
}
</style>
