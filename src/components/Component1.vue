<template>
  <div class="component-1-8">
    <p class="text-81 valign-text-middle inter-semi-bold-jordy-blue-13px">{{ children }}</p>
  </div>
</template>

<script>
export default {
  name: "Component1",
  props: ["children"],
};
</script>

<style>
.component-1-8 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  position: relative;
}

.text-81 {
  letter-spacing: 0;
  line-height: 18.5px;
  margin-top: -1px;
  position: relative;
  text-decoration: underline;
  white-space: nowrap;
  width: fit-content;
}
</style>
