<template>
  <article class="component-3-46">
    <margin2 />
    <div class="container-682">
      <div class="percent-85 valign-text-middle wwwcoingeckocomintersemi-bold-12">{{ percent }}</div>
    </div>
  </article>
</template>

<script>
import Margin2 from "./Margin2";
export default {
  name: "Component33",
  components: {
    Margin2,
  },
  props: ["percent"],
};
</script>

<style>
.component-3-46 {
  align-items: center;
  border: 1px solid;
  border-color: var(--mischka);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 8px 12px 6px;
  position: relative;
}

.container-682 {
  align-items: center;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
  z-index: 0;
}

.percent-85 {
  color: var(--dhancowhite);
  font-weight: 600;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: center;
  white-space: nowrap;
  width: fit-content;
}
</style>
