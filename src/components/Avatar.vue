<template>
  <div :class="[`avatar`, className || ``]"><iconfilluser :className="iconfilluserProps.className" /></div>
</template>

<script>
import Iconfilluser from "./Iconfilluser";
export default {
  name: "Avatar",
  components: {
    Iconfilluser,
  },
  props: ["className", "iconfilluserProps"],
};
</script>

<style>
.avatar {
  align-items: flex-end;
  background-color: var(--ebony);
  border-radius: 200px;
  display: flex;
  gap: 10px;
  height: 43px;
  justify-content: center;
  position: relative;
  width: 68px;
}

.avatar.avatar-2 {
  cursor: pointer;
  transition: all 0.2s ease;
}

.avatar.avatar-2:hover {
  box-shadow: 0px 0px 10px 2px rgba(0, 0, 0, 0.2);
}

.avatar.avatar-6 {
  background-color: unset;
  height: 29px;
  width: 64px;
}

.avatar.avatar-8,
.avatar.avatar-9,
.avatar.avatar-11,
.avatar.avatar-13 {
  background-color: unset;
  height: 35px;
  width: 64px;
}

.avatar.avatar-10,
.avatar.avatar-12 {
  background-color: unset;
  height: 57px;
  width: 64px;
}
</style>
