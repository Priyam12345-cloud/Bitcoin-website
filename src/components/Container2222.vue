<template>
  <div :class="[`container-27-1`, className || ``]">
    <div class="number-2 valign-text-middle dhancointerregular-1219">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Container2222",
  props: ["children", "className"],
};
</script>

<style>
.container-27-1 {
  align-items: flex-start;
  bottom: -47px;
  display: flex;
  flex-direction: column;
  left: 82.69%;
  position: absolute;
  width: 16.37%;
}

.number-2 {
  -webkit-background-clip: text !important;
  -webkit-text-fill-color: transparent;
  background: linear-gradient(180deg, rgb(255, 255, 255) 0%, rgb(255, 255, 255) 79.45%);
  background-clip: text;
  color: transparent;
  font-weight: 400;
  line-height: 182.9px;
  margin-right: -8.16px;
  margin-top: -1px;
  position: relative;
  text-fill-color: transparent;
  white-space: nowrap;
  width: fit-content;
}

.container-27-1.container-27 .number-2 {
  margin-right: -9.16px;
}
</style>
