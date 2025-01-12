<template>
  <div :class="[`border`, className || ``]">
    <div class="buy-56 valign-text-middle wwwcoingeckocomsemanticlink">Buy</div>
  </div>
</template>

<script>
export default {
  name: "Border",
  props: ["className"],
};
</script>

<style>
.border {
  align-items: center;
  border: 1px solid;
  border-color: var(--screamin-green);
  border-radius: 6px;
  display: flex;
  flex-direction: column;
  height: 18px;
  left: 447px;
  padding: 1px 7.52px 1px 7.51px;
  position: absolute;
  top: 1166px;
  width: 37px;
}

.buy-56 {
  align-self: stretch;
  color: var(--screamin-green);
  font-weight: 500;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: center;
}

.border.border-1 {
  height: 17px;
  top: 1235px;
}

.border.border-2 {
  top: 1300px;
}

.border.border-3 {
  height: 19px;
  top: 1369px;
}

.border.border-4 {
  top: 1437px;
}

.border.border-5 {
  top: 1506px;
}

.border.border-6 {
  top: 1574px;
}

.border.border-7 {
  height: 19px;
  top: 1641px;
}
</style>
