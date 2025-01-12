<template>
  <footer class="footer">
    <div class="container-29"></div>
    <container42 :container42Props="component3Props.container42Props" />
    <container522 />
    <container722 :component3Props="component3Props32.component3Props" />
    <container522 />
  </footer>
</template>

<script>
import Container42 from "./Container42";
import Container522 from "./Container522";
import Container722 from "./Container722";
export default {
  name: "Footer3",
  components: {
    Container42,
    Container522,
    Container722,
  },
  props: ["component3Props", "component3Props32"],
};
</script>

<style>
.footer {
  align-items: center;
  background-color: transparent;
  display: flex;
  flex-direction: column;
  gap: 24px;
  left: 62px;
  position: absolute;
  top: 0;
  width: 1266px;
}

.container-29 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  justify-content: center;
  position: relative;
  width: 100%;
}
</style>
