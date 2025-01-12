<template>
  <div class="frame-14348-3">
    <div class="crypto-war valign-text-middle taviraj-bold-white-40px-2">{{ cryptoWar2 }}</div>
    <div class="prize-pool-4 valign-text-middle taviraj-semi-bold-white-34px">Prize Pool</div>
    <div class="frame-14362-6">
      <img
        class="rupee-245"
        src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/rupee-376@2x.png"
        alt="Rupee"
      />
      <div class="address-45 valign-text-middle taviraj-extra-bold-white-36px">{{ address }}</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Frame143483",
  props: ["cryptoWar2", "address"],
};
</script>

<style>
.frame-14348-3,
.frame-14348-4 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  gap: 3px;
  position: relative;
}

.crypto-war,
.place-34,
.ai-big-data {
  -webkit-background-clip: text !important;
  -webkit-text-fill-color: transparent;
  background: linear-gradient(
    180deg,
    rgb(249, 217, 5) 0%,
    rgba(252, 236, 130, 0.8) 50%,
    rgb(253.5, 245.5, 192.5) 75%,
    rgba(255, 255, 255, 0.8) 100%
  );
  background-clip: text;
  height: 71px;
  letter-spacing: 0;
  line-height: 32px;
  margin-top: -1px;
  position: relative;
  text-fill-color: transparent;
  width: 349px;
}

.prize-pool-4,
.prize-pool-5 {
  height: 42px;
  letter-spacing: 0;
  line-height: 32px;
  position: relative;
  width: 222px;
}

.frame-14362-6,
.frame-14362-7 {
  align-items: center;
  display: flex;
  gap: 3px;
  height: 38px;
  position: relative;
  width: 222px;
}

.rupee-245,
.rupee-246 {
  height: 35.19px;
  margin-left: -2.52px;
  position: relative;
  width: 24.52px;
}

.address-45,
.address-46 {
  letter-spacing: 0;
  line-height: 32px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}
</style>
