<template>
  <a href="javascript:SubmitForm('form5')">
    <div class="frame-262"><social-media-signuplogin :children="socialMediaSignuploginProps.children" /></div
  ></a>
</template>

<script>
import SocialMediaSignuplogin from "./SocialMediaSignuplogin";
export default {
  name: "Frame261",
  components: {
    SocialMediaSignuplogin,
  },
  props: ["socialMediaSignuploginProps"],
};
</script>

<style>
.frame-262 {
  align-items: center;
  cursor: pointer;
  display: flex;
  gap: 24px;
  height: 200px;
  justify-content: center;
  left: 502px;
  position: absolute;
  top: 511px;
  transition: all 0.2s ease;
  width: 300px;
}

.frame-262:hover {
  transform: scale(1.1);
}
</style>
