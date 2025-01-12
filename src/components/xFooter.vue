<template>
  <footer :class="[`footer-1`, className || ``]">
    <div class="container-423"></div>
    <container42 :container42Props="container4Props.container42Props" />
    <container522 :className="container7Props2.className" />
    <container722 :component3Props="container7Props22.component3Props" />
    <container522 :className="container7Props23.className" />
    <div class="container-424"></div>
  </footer>
</template>

<script>
import Container42 from "./Container42";
import Container522 from "./Container522";
import Container722 from "./Container722";
export default {
  name: "xFooter",
  components: {
    Container42,
    Container522,
    Container722,
  },
  props: ["className", "container4Props", "container7Props2", "container7Props22", "container7Props23"],
};
</script>

<style>
.footer-1 {
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

.container-423 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  justify-content: center;
  position: relative;
  width: 100%;
}

.container-424 {
  align-items: center;
  align-self: stretch;
  display: flex;
  height: 22px;
  justify-content: center;
  position: relative;
  width: 100%;
}

.footer-1.footer-2 {
  left: 116px;
  top: 3974px;
}

.footer-1.footer-7 {
  top: 23px;
}

.footer-1.footer-19 {
  left: 1px;
  top: 676px;
}

.footer-1.footer-21 {
  left: 68px;
  top: 20px;
}
</style>
