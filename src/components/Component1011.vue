<template>
  <div class="component-10-11">
    <div class="container-680">
      <div class="container-681">
        <div class="cryptocurrency valign-text-middle taviraj-semi-bold-white-12px">{{ children }}</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Component1011",
  props: ["children"],
};
</script>

<style>
.component-10-11 {
  align-items: center;
  background-color: var(--ebony);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.container-680 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.container-681 {
  align-items: flex-end;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
  width: 100%;
}

.cryptocurrency {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
