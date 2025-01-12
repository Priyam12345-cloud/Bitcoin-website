<template>
  <div :class="[`frame-14348-7`, className || ``]">
    <div class="prize-pool-8 valign-text-middle taviraj-bold-white-45px">Prize pool</div>
    <div class="frame-14361-6">
      <div class="address-55 valign-text-middle taviraj-extra-bold-white-48px">{{ address }}</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Frame14348",
  props: ["address", "className"],
};
</script>

<style>
.frame-14348-7 {
  align-items: flex-start;
  display: flex;
  flex-direction: column;
  gap: 12px;
  height: 203px;
  margin-bottom: -104px;
  margin-top: -104px;
  position: relative;
  width: 211px;
}

.prize-pool-8 {
  height: 44px;
  letter-spacing: 0;
  line-height: 32px;
  margin-right: -44px;
  margin-top: -1px;
  position: relative;
  width: 255px;
}

.frame-14361-6 {
  align-items: flex-start;
  display: flex;
  gap: 3px;
  height: 47px;
  justify-content: flex-end;
  position: relative;
  width: 201px;
}

.address-55 {
  letter-spacing: 0;
  line-height: 32px;
  margin-left: -81px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  width: 282px;
}

.frame-14348-7.frame-14348-8,
.frame-14348-7.frame-14348-10 {
  height: 149px;
  margin-bottom: -77px;
  margin-top: -77px;
}

.frame-14348-7.frame-14348-8 .prize-pool-8,
.frame-14348-7.frame-14348-10 .prize-pool-8 {
  margin-right: -56px;
  width: 267px;
}
</style>
