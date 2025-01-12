<template>
  <div class="coin-info-1">
    <div class="frame-106-1">
      <img
        class="coin-icon-3"
        src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777a4880cdd8fda588782fc/img/coin-icon-36@2x.png"
        alt="coin-icon"
      />
      <div class="btc-3 taviraj-extra-bold-white-20px">ETH</div>
      <div class="frame-13-1"><div class="bitcoin-4 taviraj-bold-black-12px">ETHEREUM</div></div>
    </div>
    <see-more-ic :className="seeMoreIcProps.className" />
  </div>
</template>

<script>
import SeeMoreIc from "./SeeMoreIc";
export default {
  name: "CoinInfo2",
  components: {
    SeeMoreIc,
  },
  props: ["seeMoreIcProps"],
};
</script>

<style>
.coin-info-1 {
  align-items: center;
  display: flex;
  flex: 0 0 auto;
  justify-content: space-between;
  position: relative;
  width: 254px;
}

.frame-106-1 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 14px;
  position: relative;
}

.coin-icon-3 {
  height: 50px;
  position: relative;
  width: 50px;
}

.btc-3,
.btc-4 {
  letter-spacing: 0;
  line-height: normal;
  position: relative;
  width: fit-content;
}

.frame-13-1 {
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

.bitcoin-4 {
  letter-spacing: 0;
  line-height: normal;
  margin-top: -1px;
  position: relative;
  text-align: center;
  width: fit-content;
}
</style>
