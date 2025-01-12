<template>
  <div class="component-10-10">
    <div class="container-678">
      <div class="container-679">
        <div class="bitcoin-ecosystem valign-text-middle taviraj-semi-bold-white-12px">{{ children }}</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Component1010",
  props: ["children"],
};
</script>

<style>
.component-10-10 {
  align-items: center;
  background-color: var(--ebony);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.container-678 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.container-679 {
  align-items: flex-end;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
  width: 100%;
}

.bitcoin-ecosystem {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
