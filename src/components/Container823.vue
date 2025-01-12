<template>
  <div :class="[`container-661`, className || ``]">
    <div class="ledger valign-text-middle wwwcoingeckocomintersemi-bold-12">{{ children }}</div>
  </div>
</template>

<script>
export default {
  name: "Container823",
  props: ["children", "className"],
};
</script>

<style>
.container-661 {
  align-items: flex-end;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.ledger {
  color: var(--dhancowhite);
  font-weight: 600;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.container-661.container-662 {
  align-items: center;
}

.container-661.container-662 .ledger {
  text-align: center;
}
</style>
