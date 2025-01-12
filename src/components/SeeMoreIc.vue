<template>
  <div :class="[`see-more-ic`, className || ``]">
    <div class="overlap-group-12">
      <img
        class="vector-3-1"
        src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777a4880cdd8fda588782fc/img/vector-3-19@2x.png"
        alt="Vector 3"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "SeeMoreIc",
  props: ["className"],
};
</script>

<style>
.see-more-ic {
  height: 48px;
  position: relative;
  width: 48px;
}

.overlap-group-12 {
  align-items: flex-start;
  background-color: var(--ebony);
  border-radius: 20px;
  display: flex;
  height: 34px;
  justify-content: flex-end;
  left: 7px;
  min-width: 34px;
  padding: 8.1px 8.6px;
  position: relative;
  top: 7px;
}

.vector-3-1 {
  height: 16px;
  width: 16px;
}

.see-more-ic.see-more-ic-1,
.see-more-ic.see-more-ic-1-1 {
  margin-left: -4px;
}

.see-more-ic.see-more-ic-1-1 .overlap-group-12 {
  background-color: var(--blue-charcoal);
  border-radius: 15px;
}

.see-more-ic.see-more-ic-1 .overlap-group-12 {
  background-color: var(--blue-charcoal);
}
</style>
