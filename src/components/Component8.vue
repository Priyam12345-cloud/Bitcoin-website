<template>
  <article class="component-8-9">
    <div class="container-639">
      <div class="surname-15 valign-text-middle taviraj-semi-bold-white-14px">{{ children }}</div>
    </div>
  </article>
</template>

<script>
export default {
  name: "Component8",
  props: ["children"],
};
</script>

<style>
.component-8-9 {
  align-items: center;
  background-color: #ffffff21;
  border-radius: 6px;
  display: inline-flex;
  flex: 0 0 auto;
  padding: 4px 10px;
  position: relative;
}

.container-639 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.surname-15 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}
</style>
