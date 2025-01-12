<template>
  <div class="data-472">
    <div class="link-47"><paragraph :children="paragraphProps.children" :className="paragraphProps.className" /></div>
  </div>
</template>

<script>
import Paragraph from "./Paragraph";
export default {
  name: "Data15",
  components: {
    Paragraph,
  },
  props: ["paragraphProps"],
};
</script>

<style>
.data-472,
.data-473 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 27px 10px 22.5px;
  position: relative;
  width: 324.05px;
}

.link-47,
.link-48 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  margin-bottom: -0.5px;
  position: relative;
  width: 100%;
}
</style>
