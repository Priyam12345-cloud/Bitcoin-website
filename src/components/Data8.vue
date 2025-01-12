<template>
  <div :class="[`data-54-1`, className || ``]">
    <div class="link-23">
      <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
      <div class="paragraph-20">
        <div class="cronos valign-text-middle inter-semi-bold-white-lilac-17px">{{ cronos }}</div>
      </div>
    </div>
  </div>
</template>

<script>
import Imgmargin from "./Imgmargin";
export default {
  name: "Data8",
  components: {
    Imgmargin,
  },
  props: ["cronos", "className", "imgmarginProps"],
};
</script>

<style>
.data-54-1 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-23 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-20 {
  display: flex;
  height: 20px;
  position: relative;
  width: 78.19px;
}

.cronos {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: -0.3px;
  margin-top: -0.5px;
  white-space: nowrap;
  width: 72px;
}

.data-54-1.data-54 .paragraph-20,
.data-54-1.data-56 .paragraph-20 {
  width: 77.84px;
}

.data-54-1.data-54 .cronos,
.data-54-1.data-56 .cronos {
  width: 65px;
}
</style>
