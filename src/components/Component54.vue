<template>
  <div :class="[`component-55`, className || ``]">
    <data462 :className="data462Props.className" :container2Props="data462Props.container2Props" />
    <data2 :children="data2Props.children" :className="data2Props.className" />
    <imgmargin3 />
    <data12 :paragraph6Props="data12Props.paragraph6Props" />
    <div class="data-480"></div>
    <div class="data-481"></div>
    <img
      class="rupee-234"
      src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/rupee-292@2x.png"
      alt="Rupee"
    />
    <data3 :children="data3Props.children" />
    <div class="data-482"></div>
    <img
      class="rupee-235"
      src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/rupee-37@2x.png"
      alt="Rupee"
    />
    <data13 :className="data13Props.className" :data14Props="data13Props.data14Props" />
  </div>
</template>

<script>
import Data462 from "./Data462";
import Data2 from "./Data2";
import Imgmargin3 from "./Imgmargin3";
import Data12 from "./Data12";
import Data3 from "./Data3";
import Data13 from "./Data13";
export default {
  name: "Component54",
  components: {
    Data462,
    Data2,
    Imgmargin3,
    Data12,
    Data3,
    Data13,
  },
  props: ["className", "data462Props", "data2Props", "data12Props", "data3Props", "data13Props"],
};
</script>

<style>
.component-55 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  height: 69px;
  justify-content: center;
  margin-left: 68px;
  position: relative;
  width: 1088px;
}

.data-480 {
  background-color: var(--black);
  height: 69px;
  position: relative;
  width: 111.17px;
}

.data-481 {
  background-color: var(--black);
  height: 69px;
  position: relative;
  width: 74.97px;
}

.rupee-234 {
  height: 21.53px;
  position: relative;
  width: 15.49px;
}

.data-482 {
  background-color: var(--black);
  height: 69px;
  position: relative;
  width: 154.3px;
}

.rupee-235 {
  height: 21.53px;
  position: relative;
  width: 15.49px;
}

.component-55.component-56-1 .rupee-234,
.component-55.component-56-1 .rupee-235,
.component-55.component-56 .rupee-234,
.component-55.component-56 .rupee-235 {
  height: 21.53px;
}
</style>
