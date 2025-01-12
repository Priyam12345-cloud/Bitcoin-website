<template>
  <div :class="[`data-69-1`, className || ``]">
    <div class="link-29">
      <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
      <div class="paragraph-25">
        <div class="injective valign-text-middle inter-semi-bold-white-lilac-17px">{{ injective }}</div>
      </div>
    </div>
  </div>
</template>

<script>
import Imgmargin from "./Imgmargin";
export default {
  name: "Data9",
  components: {
    Imgmargin,
  },
  props: ["injective", "className", "imgmarginProps"],
};
</script>

<style>
.data-69-1 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-29 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-25 {
  display: flex;
  height: 20px;
  position: relative;
  width: 80.17px;
}

.injective {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: -0.3px;
  margin-top: -0.5px;
  white-space: nowrap;
  width: 81px;
}

.data-69-1.data-69 .paragraph-25,
.data-69-1.data-70 .paragraph-25 {
  width: 79.89px;
}

.data-69-1.data-69 .injective,
.data-69-1.data-70 .injective {
  width: 68px;
}
</style>
