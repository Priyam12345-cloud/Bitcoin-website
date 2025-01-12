<template>
  <article class="coin-trend-item-5" name="1_5661" :placeholder="inputPlaceholder" :type="inputType" />
</template>

<script>
import CoinInfo2 from "./CoinInfo2";
import CoinValue from "./CoinValue";
export default {
  name: "CoinTrendItem5",
  components: {
    CoinInfo2,
    CoinValue,
  },
  props: ["inputType", "inputPlaceholder", "coinInfo2Props", "coinValueProps"],
};
</script>

<style>
.coin-trend-item-5 {
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

.coin-trend-item-5:hover {
  transform: scale(1.1);
}

.divider-4 {
  background-color: var(--font-colorlight-title);
  height: 1px;
  opacity: 0.5;
  position: relative;
  width: 258px;
}
</style>
