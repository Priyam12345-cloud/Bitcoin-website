<template>
  <textarea class="coin-trend-item-2" name="1_4437" :placeholder="inputPlaceholder" :type="inputType"></textarea>
</template>

<script>
import CoinInfo2 from "./CoinInfo2";
export default {
  name: "CoinTrendItem2",
  components: {
    CoinInfo2,
  },
  props: ["inputType", "inputPlaceholder", "x5662354", "x141", "chartState1", "coinInfo2Props"],
};
</script>

<style>
.coin-trend-item-2 {
  -webkit-backdrop-filter: blur(200px) brightness(100%);
  align-items: center;
  align-self: stretch;
  backdrop-filter: blur(200px) brightness(100%);
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

.coin-trend-item-2:hover {
  transform: scale(1.1);
}

.divider-1 {
  background-color: var(--font-colorlight-title);
  height: 1px;
  opacity: 0.5;
  position: relative;
  width: 258px;
}

.coin-value-1 {
  align-items: center;
  display: flex;
  flex: 0 0 auto;
  justify-content: space-between;
  position: relative;
  width: 252px;
}

.frame-108-1 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  gap: 9px;
  justify-content: center;
  position: relative;
  width: 140px;
}

.x5662354-1 {
  align-self: stretch;
  letter-spacing: 0;
  line-height: normal;
  margin-top: -1px;
  position: relative;
}

.x141 {
  align-self: stretch;
  letter-spacing: 0;
  line-height: 28.8px;
  position: relative;
  text-align: center;
}

.chart-state-1-1 {
  height: 53.27px;
  object-fit: cover;
  position: relative;
  width: 100px;
}
</style>
