<template>
  <div :class="[`component-60-1`, className || ``]">
    <data462 :className="data462Props.className" :container2Props="data462Props.container2Props" />
    <data210 :children="data2Props.children" :className="data2Props.className" />
    <div class="data-512">
      <div class="link-51">
        <div class="paragraph-77">
          <div class="overlap-group-35">
            <p class="name-8 valign-text-middle taviraj-semi-bold-white-lilac-16px">{{ name2 }}</p>
            <img
              class="ellipse-2-4"
              src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/ellipse-2-4@2x.png"
              alt="Ellipse 2"
            />
          </div>
        </div>
      </div>
    </div>
    <div class="data-513"></div>
    <div class="data-514"></div>
    <div class="data-515"></div>
    <img
      class="rupee-264"
      src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/rupee-397@2x.png"
      alt="Rupee"
    />
    <data310 :children="data3Props.children" />
    <img
      class="rupee-264 variant-1"
      src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777f4b7a3077da4034b0dbf/img/rupee-398@2x.png"
      alt="Rupee"
    />
    <data410 />
  </div>
</template>

<script>
import Data462 from "./Data462";
import Data210 from "./Data210";
import Data310 from "./Data310";
import Data410 from "./Data410";
export default {
  name: "Component13",
  components: {
    Data462,
    Data210,
    Data310,
    Data410,
  },
  props: ["name2", "className", "data462Props", "data2Props", "data3Props"],
};
</script>

<style>
.component-60-1 {
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

.data-512 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px 22.5px 60px;
  position: relative;
  width: 324.05px;
}

.link-51 {
  align-items: center;
  align-self: stretch;
  display: flex;
  height: 17px;
  position: relative;
  width: 100%;
}

.paragraph-77 {
  height: 20px;
  margin-bottom: -1.5px;
  margin-top: -1.5px;
  position: relative;
  width: 43px;
}

.overlap-group-35 {
  height: 40px;
  left: -23px;
  position: relative;
  top: -2px;
  width: 141px;
}

.name-8 {
  height: 40px;
  left: 23px;
  letter-spacing: 0;
  line-height: 20px;
  position: absolute;
  top: 0;
  width: 118px;
}

.ellipse-2-4 {
  height: 33px;
  left: 0;
  position: absolute;
  top: 1px;
  width: 32px;
}

.data-513 {
  background-color: var(--black);
  height: 69px;
  position: relative;
  width: 111.17px;
}

.data-514 {
  background-color: var(--black);
  height: 69px;
  position: relative;
  width: 74.97px;
}

.data-515 {
  background-color: var(--black);
  height: 69px;
  position: relative;
  width: 155px;
}

.rupee-264 {
  height: 21.53px;
  position: relative;
  width: 15.49px;
}

.component-60-1.component-61-2 .rupee-264,
.component-60-1.component-61-3 .rupee-264,
.component-60-1.component-61-4 .rupee-264,
.component-60-1.component-61-5 .rupee-264,
.component-60-1.component-61-6 .rupee-264,
.component-60-1.component-61-7 .rupee-264,
.component-60-1.component-61-8 .rupee-264,
.component-60-1.component-61-9 .rupee-264,
.component-60-1.component-61-10 .rupee-264,
.component-60-1.component-61 .rupee-264 {
  height: 21.53px;
}

.component-60-1.component-61-2 .rupee-264.variant-1,
.component-60-1.component-61-3 .rupee-264.variant-1,
.component-60-1.component-61-4 .rupee-264.variant-1,
.component-60-1.component-61-5 .rupee-264.variant-1,
.component-60-1.component-61-6 .rupee-264.variant-1,
.component-60-1.component-61-7 .rupee-264.variant-1,
.component-60-1.component-61-8 .rupee-264.variant-1,
.component-60-1.component-61-9 .rupee-264.variant-1,
.component-60-1.component-61-10 .rupee-264.variant-1,
.component-60-1.component-61 .rupee-264.variant-1 {
  position: relative;
  width: 15.49px;
}
</style>
