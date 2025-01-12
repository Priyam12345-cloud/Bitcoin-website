<template>
  <div class="data-410">
    <div class="link-41">
      <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
      <paragraph32 :solana="paragraphProps.solana" :sol="paragraphProps.sol" :className="paragraphProps.className" />
    </div>
  </div>
</template>

<script>
import Imgmargin from "./Imgmargin";
import Paragraph32 from "./Paragraph32";
export default {
  name: "Data16",
  components: {
    Imgmargin,
    Paragraph32,
  },
  props: ["imgmarginProps", "paragraphProps"],
};
</script>

<style>
.data-410,
.data-411 {
  align-items: flex-start;
  background-color: var(--ebony);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-41,
.link-42 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}
</style>
