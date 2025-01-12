<template>
  <div :class="[`component-62`, className || ``]">
    <data462 :className="data462Props.className" :container2Props="data462Props.container2Props" />
    <data210 :children="data2Props.children" :className="data2Props.className" />
    <div class="data-520">
      <div class="link-53">
        <div class="paragraph-79">
          <div class="overlap-group-37">
            <p class="name-2-1 valign-text-middle inter-semi-bold-white-lilac-16px">{{ name24 }}</p>
            <img
              class="ellipse-2-6"
              src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/ellipse-2-4@2x.png"
              alt="Ellipse 2"
            />
          </div>
        </div>
      </div>
      <div class="imgmargin-12"></div>
    </div>
    <div class="data-521"></div>
    <data6 :className="data3Props.className" />
    <div class="data-522"></div>
    <img
      class="rupee-267"
      src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/rupee-397@2x.png"
      alt="Rupee"
    />
    <data310 :children="data3Props2.children" />
    <img
      class="rupee-267 variant-1"
      src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/rupee-398@2x.png"
      alt="Rupee"
    />
    <data410 />
  </div>
</template>

<script>
import Data462 from "./Data462";
import Data210 from "./Data210";
import Data6 from "./Data6";
import Data310 from "./Data310";
import Data410 from "./Data410";
export default {
  name: "Component1122",
  components: {
    Data462,
    Data210,
    Data6,
    Data310,
    Data410,
  },
  props: ["name24", "className", "data462Props", "data2Props", "data3Props", "data3Props2"],
};
</script>

<style>
.component-62 {
  align-items: center;
  align-self: stretch;
  background-color: var(--black);
  display: flex;
  gap: 4px;
  height: 69px;
  justify-content: center;
  position: relative;
  width: 100%;
}

.data-520 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px 22.5px 60px;
  position: relative;
  width: 324.05px;
}

.link-53 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-79 {
  height: 19px;
  position: relative;
  width: 154px;
}

.overlap-group-37 {
  height: 33px;
  left: -24px;
  position: relative;
  top: -6px;
  width: 137px;
}

.name-2-1 {
  height: 27px;
  left: 24px;
  letter-spacing: 0;
  line-height: 20px;
  position: absolute;
  top: 5px;
  width: 113px;
}

.ellipse-2-6 {
  height: 33px;
  left: 0;
  position: absolute;
  top: 0;
  width: 32px;
}

.imgmargin-12 {
  height: 10px;
  margin-bottom: -5px;
  max-width: 312.05px;
  position: relative;
  width: 32px;
}

.data-521 {
  background-color: var(--black);
  height: 69px;
  position: relative;
  width: 111.17px;
}

.data-522 {
  background-color: var(--black);
  height: 69px;
  position: relative;
  width: 155px;
}

.rupee-267 {
  height: 21.53px;
  position: relative;
  width: 15.49px;
}

.component-62.component-63-1 .rupee-267,
.component-62.component-63 .rupee-267 {
  height: 21.53px;
}

.component-62.component-63-1 .rupee-267.variant-1,
.component-62.component-63 .rupee-267.variant-1 {
  position: relative;
  width: 15.49px;
}
</style>
