<template>
  <div :class="[`component-11-3-1`, className || ``]">
    <data462 :container2Props="data462Props.container2Props" />
    <data2 :children="data2Props.children" :className="data2Props.className" />
    <div class="data-63">
      <div class="link-27">
        <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
        <div class="paragraph-23">
          <div class="render valign-text-middle inter-semi-bold-white-lilac-17px">{{ render }}</div>
        </div>
      </div>
    </div>
    <img
      class="rupee-39"
      src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/rupee-36@2x.png"
      alt="Rupee"
    />
    <data3 :children="data3Props.children" :className="data3Props.className" />
    <div class="data-64"></div>
    <data4 :children="data4Props.children" />
    <div class="data-65"></div>
    <img
      class="rupee-39 variant-1"
      src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/rupee-37@2x.png"
      alt="Rupee"
    />
    <data5 :children="data5Props.children" />
  </div>
</template>

<script>
import Data462 from "./Data462";
import Data2 from "./Data2";
import Imgmargin from "./Imgmargin";
import Data3 from "./Data3";
import Data4 from "./Data4";
import Data5 from "./Data5";
export default {
  name: "Component112",
  components: {
    Data462,
    Data2,
    Imgmargin,
    Data3,
    Data4,
    Data5,
  },
  props: [
    "render",
    "className",
    "data462Props",
    "data2Props",
    "imgmarginProps",
    "data3Props",
    "data4Props",
    "data5Props",
  ],
};
</script>

<style>
.component-11-3-1 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  height: 69px;
  justify-content: center;
  margin-left: -13px;
  margin-right: -13px;
  position: relative;
  width: 1114px;
}

.data-63 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-27 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-23 {
  display: flex;
  height: 20px;
  position: relative;
  width: 99.67px;
}

.render {
  height: 20px;
  letter-spacing: 0;
  line-height: 20px;
  margin-left: -0.3px;
  margin-top: -0.5px;
  white-space: nowrap;
  width: 67px;
}

.rupee-39 {
  height: 21.53px;
  position: relative;
  width: 15.49px;
}

.data-64 {
  background-color: var(--black);
  height: 69px;
  position: relative;
  width: 111.17px;
}

.data-65 {
  background-color: var(--black);
  height: 69px;
  position: relative;
  width: 74.97px;
}

.component-11-3-1.component-11-3 .paragraph-23,
.component-11-3-1.component-11-4 .paragraph-23 {
  width: 99.02px;
}

.component-11-3-1.component-11-3 .render,
.component-11-3-1.component-11-4 .render {
  width: 89px;
}

.component-11-3-1.component-11-4-1 .rupee-39,
.component-11-3-1.component-11-4 .rupee-39 {
  height: 21.53px;
}

.component-11-3-1.component-11-4-1 .rupee-39.variant-1,
.component-11-3-1.component-11-4 .rupee-39.variant-1 {
  position: relative;
  width: 15.49px;
}
</style>
