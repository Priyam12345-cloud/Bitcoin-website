<template>
  <div class="component-3-45">
    <container823 :children="container8Props.children" :className="container8Props.className" />
    <div class="margin-39"><component163 /></div>
  </div>
</template>

<script>
import Container823 from "./Container823";
import Component163 from "./Component163";
export default {
  name: "Component322",
  components: {
    Container823,
    Component163,
  },
  props: ["container8Props"],
};
</script>

<style>
.component-3-45 {
  align-items: center;
  background-color: var(--ebony);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  gap: 0.01px;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.margin-39 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  padding: 0px 0px 0px 8px;
  position: relative;
}
</style>
