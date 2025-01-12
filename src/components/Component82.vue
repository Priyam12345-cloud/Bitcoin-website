<template>
  <article class="component-8-10">
    <div class="container-640">
      <div class="market-cap-8 valign-text-middle taviraj-semi-bold-white-14px-2">{{ children }}</div>
    </div>
  </article>
</template>

<script>
export default {
  name: "Component82",
  props: ["children"],
};
</script>

<style>
.component-8-10 {
  align-items: center;
  border-radius: 6px;
  display: inline-flex;
  flex: 0 0 auto;
  padding: 4px 10px;
  position: relative;
}

.container-640 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.market-cap-8 {
  letter-spacing: 0;
  line-height: 20px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}
</style>
