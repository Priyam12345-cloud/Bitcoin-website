<template>
  <a href="javascript:SubmitForm('form5')">
    <div class="social-media-signuplogin">
      <div class="frame-7">
        <div class="continue-with-google valign-text-middle">{{ children }}</div>
      </div>
    </div></a
  >
</template>

<script>
export default {
  name: "SocialMediaSignuplogin",
  props: ["children"],
};
</script>

<style>
.social-media-signuplogin {
  align-items: center;
  background: linear-gradient(180deg, rgb(224, 194, 26) 0%, rgb(124, 110, 23) 45%, rgb(24, 25, 21) 90%);
  border: 1px solid;
  border-color: var(--mine-shaft);
  border-radius: 32px;
  cursor: pointer;
  display: flex;
  flex: 1;
  flex-grow: 1;
  height: 64px;
  justify-content: center;
  overflow: hidden;
  position: relative;
  transition: all 0.2s ease;
}

.social-media-signuplogin:hover {
  transform: scale(1.1);
}

.frame-7 {
  align-items: center;
  display: inline-flex;
  gap: 16px;
  height: 61px;
  justify-content: center;
  margin-left: 1px;
  margin-top: -1px;
  position: relative;
  width: 179px;
}

.continue-with-google {
  color: var(--dhancowhite);
  font-family: var(--font-family-taviraj);
  font-size: 36px;
  font-weight: 900;
  letter-spacing: 0;
  line-height: normal;
  margin-top: -1px;
  position: relative;
  width: fit-content;
}
</style>
