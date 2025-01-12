<template>
  <div :class="[`data-760-1`, className || ``]">
    <div class="link-58">
      <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
      <div class="paragraph-187">
        <div class="overlap-group-82">
          <div class="tron-4 valign-text-middle wwwcoingeckocomintersemi-bold-14">{{ tron }}</div>
          <div class="trx-2 valign-text-middle wwwcoingeckocomsemanticlink">{{ trx }}</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Imgmargin from "./Imgmargin";
export default {
  name: "Data79",
  components: {
    Imgmargin,
  },
  props: ["tron", "trx", "className", "imgmarginProps"],
};
</script>

<style>
.data-760-1 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-58 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-187 {
  height: 20px;
  position: relative;
  width: 67.33px;
}

.overlap-group-82 {
  height: 20px;
  position: relative;
  top: -2px;
  width: 68px;
}

.tron-4 {
  color: var(--white-lilac);
  font-weight: 600;
  height: 20px;
  left: 0;
  line-height: 20px;
  position: absolute;
  top: 0;
  white-space: nowrap;
  width: 44px;
}

.trx-2 {
  color: var(--white);
  font-weight: 500;
  height: 16px;
  left: 43px;
  line-height: 16px;
  position: absolute;
  top: 3px;
  white-space: nowrap;
  width: 24px;
}

.data-760-1.data-760 .paragraph-187 {
  width: 67.53px;
}
</style>
