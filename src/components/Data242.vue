<template>
  <div :class="[`data-454-1`, className || ``]">
    <div class="link-43">
      <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
      <div class="paragraph-63">
        <div class="place-21 valign-text-middle taviraj-semi-bold-white-lilac-15px">{{ place1 }}</div>
      </div>
      <div class="place-22 valign-text-middle taviraj-bold-lemon-11px">{{ place2 }}</div>
    </div>
  </div>
</template>

<script>
import Imgmargin from "./Imgmargin";
export default {
  name: "Data242",
  components: {
    Imgmargin,
  },
  props: ["place1", "place2", "className", "imgmarginProps"],
};
</script>

<style>
.data-454-1 {
  align-items: flex-start;
  background-color: var(--ebony);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-43 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-63 {
  display: flex;
  height: 20px;
  position: relative;
  width: 67.53px;
}

.place-21 {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: 6.8px;
  margin-top: 0.8px;
  white-space: nowrap;
  width: 55px;
}

.place-22 {
  height: 16px;
  letter-spacing: 0;
  line-height: 16px;
  position: relative;
  white-space: nowrap;
  width: 33px;
}

.data-454-1.data-454 .paragraph-63 {
  width: 67.63px;
}

.data-454-1.data-454 .place-21 {
  margin-left: 6.5px;
  margin-top: 0.4px;
  width: 38.06px;
}

.data-454-1.data-454 .place-22 {
  width: 40px;
}
</style>
