<template>
  <div class="data-73">
    <div class="link-31">
      <imgmargin2 />
      <paragraph22 :children="paragraph2Props.children" :className="paragraph2Props.className" />
    </div>
  </div>
</template>

<script>
import Imgmargin2 from "./Imgmargin2";
import Paragraph22 from "./Paragraph22";
export default {
  name: "Data11",
  components: {
    Imgmargin2,
    Paragraph22,
  },
  props: ["paragraph2Props"],
};
</script>

<style>
.data-73,
.data-74 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-31,
.link-32 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}
</style>
