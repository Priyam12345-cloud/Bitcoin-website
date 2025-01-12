<template>
  <div :class="[`data-8`, className || ``]"><container2 :className="container2Props.className" /></div>
</template>

<script>
import Container2 from "./Container2";
export default {
  name: "Data462",
  components: {
    Container2,
  },
  props: ["className", "container2Props"],
};
</script>

<style>
.data-8 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 27.5px 10px;
  position: relative;
  width: 36.77px;
}

.data-8.data-12,
.data-8.data-13 {
  background-color: var(--ebony);
  margin-left: -0.02px;
}

.data-8.data-17,
.data-8.data-20 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  margin-left: -22.47px;
  padding: 27.5px 10px;
  position: relative;
  width: 36.77px;
}

.data-8.data-14,
.data-8.data-15 {
  margin-left: -20.81px;
}

.data-8.data-9,
.data-8.data-10 {
  margin-left: -30.32px;
}

.data-8.data-16 {
  margin-left: -7.02px;
}
</style>
