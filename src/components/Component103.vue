<template>
  <div class="component-10-3">
    <div class="container-660">
      <div class="mempool valign-text-middle wwwcoingeckocomintersemi-bold-12">{{ children }}</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Component103",
  props: ["children"],
};
</script>

<style>
.component-10-3 {
  align-items: center;
  align-self: stretch;
  background-color: var(--ebony);
  border-color: var(--wwwcoingeckocomgeyser);
  border-radius: 8px 0px 0px 8px;
  border-right-style: solid;
  border-right-width: 2px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 6px 12px 6px 10px;
  position: relative;
}

.container-660 {
  align-items: flex-end;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.mempool {
  color: var(--dhancowhite);
  font-weight: 600;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
