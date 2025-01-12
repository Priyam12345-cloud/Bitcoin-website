<template>
  <article class="component-10-7">
    <div class="container-669">
      <div class="container-670">
        <div class="bitcointalkorg valign-text-middle taviraj-semi-bold-white-12px">{{ children }}</div>
      </div>
    </div>
  </article>
</template>

<script>
export default {
  name: "Component107",
  props: ["children"],
};
</script>

<style>
.component-10-7 {
  align-items: center;
  background-color: var(--ebony);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.container-669 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.container-670 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  justify-content: flex-end;
  position: relative;
  width: 100%;
}

.bitcointalkorg {
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
