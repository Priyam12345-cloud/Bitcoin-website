<template>
  <div :class="[`data-408`, className || ``]">
    <div class="link-39">
      <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
      <div class="paragraph-58">
        <div class="bnb-2 valign-text-middle taviraj-semi-bold-white-lilac-15px">
          <span
            ><span class="span-8 taviraj-semi-bold-white-lilac-15px">BNB</span
            ><span class="span-8 inter-semi-bold-white-lilac-15px"></span>
          </span>
        </div>
        <div class="bnb-3 valign-text-middle taviraj-bold-lemon-11px">BNB</div>
      </div>
    </div>
  </div>
</template>

<script>
import Imgmargin from "./Imgmargin";
export default {
  name: "Data1422",
  components: {
    Imgmargin,
  },
  props: ["className", "imgmarginProps"],
};
</script>

<style>
.data-408 {
  align-items: flex-start;
  background-color: var(--ebony);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-39 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-58 {
  display: flex;
  gap: 17.8px;
  height: 20px;
  position: relative;
  width: 71px;
}

.bnb-2 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -0.5px;
  white-space: nowrap;
  width: 33.03px;
}

.bnb-3 {
  height: 16px;
  letter-spacing: 0;
  line-height: 16px;
  margin-top: 2.8px;
  white-space: nowrap;
  width: 34px;
}

.data-408.data-409 .paragraph-58 {
  display: unset;
  gap: unset;
}

.data-408.data-409 .bnb-2 {
  left: 0;
  margin-top: unset;
  position: absolute;
  top: -2px;
  width: 33px;
}

.data-408.data-409 .bnb-3 {
  left: 51px;
  margin-top: unset;
  position: absolute;
  top: 2px;
}
</style>
