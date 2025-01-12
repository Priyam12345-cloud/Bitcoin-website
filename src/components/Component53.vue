<template>
  <div :class="[`component-5`, className || ``]">
    <img
      class="vector"
      src="https://cdn.animaapp.com/projects/6773d9dd0cdd8fda58877b3c/releases/6777a4880cdd8fda588782fc/img/vector-27@2x.png"
      alt="Vector"
    />
    <input
      class="search-coins taviraj-extra-bold-ebony-24px"
      name="searchcoins"
      placeholder=" Search Coins.."
      type="text"
    />
  </div>
</template>

<script>
export default {
  name: "Component53",
  props: ["className"],
};
</script>

<style>
.component-5 {
  align-items: center;
  background-color: var(--catskill-white);
  border-radius: 20px;
  display: flex;
  gap: 10px;
  height: 51px;
  padding: 10px;
  position: relative;
  width: 385px;
}

.vector {
  height: 28px;
  position: relative;
  width: 28px;
}

.search-coins {
  background-color: transparent;
  border: 0;
  cursor: pointer;
  height: 31px;
  letter-spacing: 0;
  line-height: 16px;
  margin-top: -1px;
  padding: 0;
  position: relative;
  transition: all 0.2s ease;
  width: 212px;
}

.search-coins::placeholder {
  color: #070d1d99;
}

.search-coins:hover {
  transform: scale(1.1);
}

.component-5.component-5-1 .search-coins:hover,
.component-5.component-5-2 .search-coins:hover,
.component-5.component-5-3 .search-coins:hover,
.component-5.component-5-4 .search-coins:hover,
.component-5.component-5-5 .search-coins:hover,
.component-5.component-5-6 .search-coins:hover,
.component-5.component-5-7 .search-coins:hover,
.component-5.component-5-8 .search-coins:hover,
.component-5.component-5-9 .search-coins:hover,
.component-5.component-5-10 .search-coins:hover,
.component-5.component-5-11 .search-coins:hover,
.component-5.component-5-12 .search-coins:hover,
.component-5.component-5-13 .search-coins:hover {
  box-shadow: 0px 0px 10px 2px rgba(0, 0, 0, 0.2);
}

.component-5.component-5-2 {
  margin-bottom: -0.5px;
  margin-top: -0.5px;
}
</style>
