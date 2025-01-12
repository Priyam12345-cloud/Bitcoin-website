<template>
  <div class="coin-info">
    <div class="frame-106">
      <img
        class="coin-icon-2"
        src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777a4880cdd8fda588782fc/img/coin-icon-35@2x.png"
        alt="coin-icon"
      />
      <div class="btc-1 taviraj-extra-bold-white-20px-2">BTC</div>
      <div class="frame-13"><div class="bitcoin-3 taviraj-bold-mirage-13px">BITCOIN</div></div>
    </div>
    <see-more-ic />
  </div>
</template>

<script>
import SeeMoreIc from "./SeeMoreIc";
export default {
  name: "CoinInfo",
  components: {
    SeeMoreIc,
  },
};
</script>

<style>
.coin-info {
  align-items: center;
  display: flex;
  flex: 0 0 auto;
  justify-content: space-between;
  position: relative;
  width: 254px;
}

.frame-106 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 14px;
  position: relative;
}

.coin-icon-2 {
  height: 50px;
  position: relative;
  width: 50px;
}

.btc-1,
.btc-2 {
  letter-spacing: 0;
  line-height: normal;
  position: relative;
  width: fit-content;
}

.frame-13 {
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

.bitcoin-3 {
  letter-spacing: 0;
  line-height: normal;
  margin-top: -1px;
  position: relative;
  text-align: center;
  width: fit-content;
}
</style>
