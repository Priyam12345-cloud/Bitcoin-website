<template>
  <article class="component-10-1">
    <div class="container-658">
      <div class="bitcoinorg valign-text-middle wwwcoingeckocomintersemi-bold-12">{{ children }}</div>
    </div>
  </article>
</template>

<script>
export default {
  name: "Component10",
  props: ["children"],
};
</script>

<style>
.component-10-1 {
  align-items: center;
  background-color: var(--ebony);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.container-658 {
  align-items: flex-end;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.bitcoinorg {
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
