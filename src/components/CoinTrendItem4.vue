<template>
  <textarea class="coin-trend-item-4" name="1_4440" placeholder=" Search Coins.." type="text"></textarea>
</template>

<script>
import SeeMoreIc from "./SeeMoreIc";
import CoinValue from "./CoinValue";
export default {
  name: "CoinTrendItem4",
  components: {
    SeeMoreIc,
    CoinValue,
  },
  props: ["coinValueProps"],
};
</script>

<style>
.coin-trend-item-4 {
  -webkit-backdrop-filter: blur(200px) brightness(100%);
  align-items: center;
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
  height: 200px;
  justify-content: center;
  overflow: hidden;
  padding: 0;
  position: relative;
  transition: all 0.2s ease;
}

.coin-trend-item-4:hover {
  transform: scale(1.1);
}

.coin-info-3 {
  align-items: center;
  display: flex;
  flex: 0 0 auto;
  justify-content: space-between;
  position: relative;
  width: 254px;
}

.frame-106-3 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 14px;
  position: relative;
}

.coin-icon-5 {
  height: 50px;
  position: relative;
  width: 50px;
}

.btc-7,
.btc-8 {
  letter-spacing: 0;
  line-height: normal;
  position: relative;
  width: fit-content;
}

.frame-13-3 {
  align-items: center;
  background-color: var(--dhancowhite);
  border-radius: 4px;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 10px;
  justify-content: center;
  padding: 4px 6px;
  position: relative;
}

.bitcoin-6 {
  letter-spacing: 0;
  line-height: normal;
  margin-top: -1px;
  position: relative;
  text-align: center;
  width: fit-content;
}

.divider-3 {
  background-color: var(--font-colorlight-title);
  height: 1px;
  opacity: 0.5;
  position: relative;
  width: 258px;
}
</style>
