<template>
  <div :class="[`total_market_capsvg`, className || ``]">
    <total-market-capsvg-fill :className="totalMarketCapsvgFillProps.className" />
  </div>
</template>

<script>
import TotalMarketCapsvgFill from "./TotalMarketCapsvgFill";
export default {
  name: "TotalMarketCapsvg",
  components: {
    TotalMarketCapsvgFill,
  },
  props: ["className", "totalMarketCapsvgFillProps"],
};
</script>

<style>
.total_market_capsvg {
  align-items: flex-start;
  display: inline-flex;
  flex: 1;
  flex-grow: 1;
  max-width: 156.59px;
  position: relative;
}

.total_market_capsvg.total_volumesvg {
  display: flex;
  flex: unset;
  flex-grow: unset;
  height: 62px;
  margin-bottom: -2px;
  margin-top: -2px;
  width: 156.59px;
}
</style>
