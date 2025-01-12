<template>
  <div class="data-731">
    <div class="link-57">
      <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
      <div class="paragraph-186">
        <div class="overlap-group-81">
          <div class="solana-5 valign-text-middle wwwcoingeckocomintersemi-bold-14">{{ bitcoin }}</div>
          <div class="sol-1 valign-text-middle wwwcoingeckocomsemanticlink">{{ btc }}</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Imgmargin from "./Imgmargin";
export default {
  name: "Data64",
  components: {
    Imgmargin,
  },
  props: ["bitcoin", "btc", "imgmarginProps"],
};
</script>

<style>
.data-731 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-57 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-186 {
  height: 20px;
  position: relative;
  width: 73.22px;
}

.overlap-group-81 {
  height: 20px;
  position: relative;
  top: -2px;
  width: 74px;
}

.solana-5 {
  color: var(--white-lilac);
  font-weight: 600;
  height: 20px;
  left: 0;
  line-height: 20px;
  position: absolute;
  top: 0;
  white-space: nowrap;
  width: 50px;
}

.sol-1 {
  color: var(--white);
  font-weight: 500;
  height: 16px;
  left: 49px;
  line-height: 16px;
  position: absolute;
  top: 3px;
  white-space: nowrap;
  width: 24px;
}
</style>
