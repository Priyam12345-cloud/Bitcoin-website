<template>
  <div :class="[`data-795-1`, className || ``]">
    <div class="link-59">
      <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
      <div class="paragraph-188">
        <div class="shib-container">
          <div class="shiba-inu-1 valign-text-middle wwwcoingeckocomintersemi-bold-14">{{ shibaInu }}</div>
          <div class="shib-1 valign-text-middle wwwcoingeckocomsemanticlink">{{ shib }}</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Imgmargin from "./Imgmargin";
export default {
  name: "Data87",
  components: {
    Imgmargin,
  },
  props: ["shibaInu", "shib", "className", "imgmarginProps"],
};
</script>

<style>
.data-795-1 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-59 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-188 {
  height: 20px;
  position: relative;
  width: 94.17px;
}

.shib-container {
  height: 20px;
  position: relative;
  top: -2px;
  width: 95px;
}

.shiba-inu-1 {
  color: var(--white-lilac);
  font-weight: 600;
  height: 20px;
  left: 0;
  line-height: 20px;
  position: absolute;
  top: 0;
  white-space: nowrap;
  width: 67px;
}

.shib-1 {
  color: var(--white);
  font-weight: 500;
  height: 16px;
  left: 66px;
  line-height: 16px;
  position: absolute;
  top: 3px;
  white-space: nowrap;
  width: 28px;
}

.data-795-1.data-795 .paragraph-188 {
  width: 93.95px;
}

.data-795-1.data-795 .shib-container {
  width: 94px;
}

.data-795-1.data-795 .shib-1 {
  left: 67px;
}
</style>
