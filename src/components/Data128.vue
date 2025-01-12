<template>
  <div :class="[`data-944-1`, className || ``]">
    <div class="link-61">
      <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
      <div class="paragraph-190">
        <div class="overlap-group-83">
          <div class="helium valign-text-middle wwwcoingeckocomintersemi-bold-14">{{ helium }}</div>
          <div class="hnt valign-text-middle wwwcoingeckocomsemanticlink">{{ hnt }}</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Imgmargin from "./Imgmargin";
export default {
  name: "Data128",
  components: {
    Imgmargin,
  },
  props: ["helium", "hnt", "className", "imgmarginProps"],
};
</script>

<style>
.data-944-1 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-61 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-190 {
  height: 20px;
  position: relative;
  width: 76.61px;
}

.overlap-group-83 {
  height: 20px;
  position: relative;
  top: -2px;
  width: 77px;
}

.helium {
  color: var(--white-lilac);
  font-weight: 600;
  height: 20px;
  left: 0;
  line-height: 20px;
  position: absolute;
  top: 0;
  white-space: nowrap;
  width: 51px;
}

.hnt {
  color: var(--white);
  font-weight: 500;
  height: 16px;
  left: 51px;
  line-height: 16px;
  position: absolute;
  top: 3px;
  white-space: nowrap;
  width: 26px;
}

.data-944-1.data-944 .paragraph-190 {
  width: 75.27px;
}

.data-944-1.data-944 .overlap-group-83 {
  width: 76px;
}

.data-944-1.data-944 .hnt {
  left: 50px;
  width: 25px;
}
</style>
