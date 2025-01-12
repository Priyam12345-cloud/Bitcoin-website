<template>
  <textarea class="coin-trend-item-1" name="1_4436" placeholder=" Search Coins.." type="text"></textarea>
</template>

<script>
import CoinInfo from "./CoinInfo";
export default {
  name: "CoinTrendItem",
  components: {
    CoinInfo,
  },
  props: ["x5662354", "percent", "className"],
};
</script>

<style>
.coin-trend-item-1 {
  align-items: center;
  align-self: stretch;
  background-color: var(--high-fidelity-colorcard-background);
  border: 0;
  border-color: var(--dhancowhite);
  border-radius: 18px;
  cursor: pointer;
  display: flex;
  flex: 1;
  flex-direction: column;
  flex-grow: 1;
  gap: 17px;
  justify-content: center;
  overflow: hidden;
  padding: 0;
  position: relative;
  transition: all 0.2s ease;
}

.coin-trend-item-1:hover {
  transform: scale(1.1);
}

.divider {
  background-color: var(--font-colorlight-title);
  height: 1px;
  opacity: 0.5;
  position: relative;
  width: 258px;
}

.coin-value {
  align-items: center;
  display: flex;
  flex: 0 0 auto;
  justify-content: space-between;
  position: relative;
  width: 252px;
}

.frame-108 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  gap: 9px;
  justify-content: center;
  position: relative;
  width: 140px;
}

.x5662354 {
  letter-spacing: 0;
  line-height: normal;
  margin-right: -13px;
  margin-top: -1px;
  position: relative;
  width: fit-content;
}

.percent-23 {
  align-self: stretch;
  letter-spacing: 0;
  line-height: 28.8px;
  position: relative;
  text-align: center;
}

.chart-state-1 {
  height: 53.27px;
  object-fit: cover;
  position: relative;
  width: 100px;
}

.coin-trend-item-1.coin-trend-item .percent-23 {
  text-align: unset;
}

.coin-trend-item-1.coin-trend-item .chart-state-1 {
  height: 53.27px;
}
</style>
