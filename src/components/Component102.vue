<template>
  <article class="component-10-2">
    <div class="container-659">
      <div class="whitepaper valign-text-middle taviraj-semi-bold-white-12px">{{ children }}</div>
    </div>
  </article>
</template>

<script>
export default {
  name: "Component102",
  props: ["children"],
};
</script>

<style>
.component-10-2 {
  align-items: center;
  background-color: var(--ebony);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.container-659 {
  align-items: flex-end;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.whitepaper {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
