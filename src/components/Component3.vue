<template>
  <div :class="[`component-3-43`, className || ``]">
    <component16 :className="component16Props.className" :container62Props="component16Props.container62Props" />
  </div>
</template>

<script>
import Component16 from "./Component16";
export default {
  name: "Component3",
  components: {
    Component16,
  },
  props: ["className", "component16Props"],
};
</script>

<style>
.component-3-43 {
  align-items: center;
  background-color: var(--ebony);
  border-radius: 0px 8px 8px 0px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  margin-left: -2.84e-14px;
  padding: 6px 10px 6px 8px;
  position: relative;
}

.component-3-43.component-3-44 {
  margin-left: unset;
}
</style>
