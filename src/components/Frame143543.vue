<template>
  <div :class="[`frame-14354-4`, className || ``]">
    <frame143483 :cryptoWar2="frame143483Props.cryptoWar2" :address="frame143483Props.address" />
    <div class="frame-14349-4">
      <p class="starts-at-1030-am valign-text-middle taviraj-bold-white-32px-2">Starts at :&nbsp;&nbsp;10:30 am</p>
      <div class="address-47 valign-text-middle taviraj-semi-bold-white-29px">1 st Prize</div>
      <div class="frame-14362-8">
        <img
          class="rupee-247"
          src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/rupee-377@2x.png"
          alt="Rupee"
        />
        <div class="address-48 valign-text-middle taviraj-extra-bold-white-32px">10 Lakh</div>
      </div>
    </div>
  </div>
</template>

<script>
import Frame143483 from "./Frame143483";
export default {
  name: "Frame143543",
  components: {
    Frame143483,
  },
  props: ["className", "frame143483Props"],
};
</script>

<style>
.frame-14354-4 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  gap: 127px;
  padding: 5px 43px;
  position: relative;
  width: 100%;
}

.frame-14349-4 {
  align-items: flex-end;
  display: flex;
  flex-direction: column;
  gap: 3px;
  justify-content: flex-end;
  position: relative;
  width: 715px;
}

.starts-at-1030-am {
  -webkit-background-clip: text !important;
  -webkit-text-fill-color: transparent;
  background: linear-gradient(180deg, rgb(255, 255, 255) 0%, rgb(153, 153, 153) 100%);
  background-clip: text;
  letter-spacing: 0;
  line-height: 32px;
  margin-left: -102px;
  margin-top: -1px;
  position: relative;
  text-fill-color: transparent;
  width: 817px;
}

.address-47 {
  height: 36px;
  letter-spacing: 0;
  line-height: 32px;
  margin-left: -127px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: 842px;
}

.frame-14362-8 {
  align-items: center;
  display: flex;
  gap: 3px;
  height: 43px;
  justify-content: flex-end;
  position: relative;
  width: 194px;
}

.rupee-247 {
  height: 34.35px;
  position: relative;
  width: 23.39px;
}

.address-48 {
  letter-spacing: 0;
  line-height: 32px;
  position: relative;
  white-space: nowrap;
  width: fit-content;
}

.frame-14354-4.frame-14354-5 .rupee-247 {
  height: 34.35px;
}
</style>
