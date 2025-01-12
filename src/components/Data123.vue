<template>
  <div :class="[`data-928-1`, className || ``]">
    <div class="link-60">
      <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
      <div class="paragraph-189">
        <div class="render-2 valign-text-middle taviraj-semi-bold-white-lilac-17px">{{ render1 }}</div>
      </div>
      <div class="render-3 valign-text-middle taviraj-bold-lemon-12px">{{ render2 }}</div>
    </div>
  </div>
</template>

<script>
import Imgmargin from "./Imgmargin";
export default {
  name: "Data123",
  components: {
    Imgmargin,
  },
  props: ["render1", "render2", "className", "imgmarginProps"],
};
</script>

<style>
.data-928-1 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px 22.5px 30px;
  position: relative;
  width: 324.05px;
}

.link-60 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-189 {
  display: flex;
  height: 20px;
  position: relative;
  width: 99.67px;
}

.render-2 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: -0.1px;
  margin-top: -1px;
  white-space: nowrap;
  width: 64px;
}

.render-3 {
  height: 16px;
  letter-spacing: 0;
  line-height: 16px;
  position: relative;
  white-space: nowrap;
  width: 63px;
}

.data-928-1.data-928 .paragraph-189 {
  width: 99.45px;
}

.data-928-1.data-928 .render-2 {
  height: 21px;
  width: 62px;
}

.data-928-1.data-928 .render-3 {
  width: 61px;
}
</style>
