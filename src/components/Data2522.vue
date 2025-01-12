<template>
  <div class="data-457">
    <div class="link-44">
      <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
      <div class="paragraph-64">
        <div class="mantra valign-text-middle taviraj-semi-bold-white-lilac-15px">{{ kaspa }}</div>
      </div>
      <p class="om valign-text-middle taviraj-bold-lemon-11px">{{ kas }}</p>
    </div>
  </div>
</template>

<script>
import Imgmargin from "./Imgmargin";
export default {
  name: "Data2522",
  components: {
    Imgmargin,
  },
  props: ["kaspa", "kas", "imgmarginProps"],
};
</script>

<style>
.data-457 {
  align-items: flex-start;
  background-color: var(--ebony);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-44 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-64 {
  display: flex;
  height: 20px;
  position: relative;
  width: 70px;
}

.mantra {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: 6.8px;
  margin-top: 0.8px;
  white-space: nowrap;
  width: 74px;
}

.om {
  height: 16px;
  letter-spacing: 0;
  line-height: 16px;
  position: relative;
  white-space: nowrap;
  width: 46px;
}
</style>
