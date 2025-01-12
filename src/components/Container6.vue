<template>
  <div :class="[`container-653`, className || ``]"><container5 :className="container5Props.className" /></div>
</template>

<script>
import Container5 from "./Container5";
export default {
  name: "Container6",
  components: {
    Container5,
  },
  props: ["className", "container5Props"],
};
</script>

<style>
.container-653 {
  align-items: flex-start;
  display: flex;
  flex: 1;
  flex-grow: 1;
  margin-right: -5.5px;
  padding: 2px 1.75px 1px;
  position: relative;
}

.container-653.container-654 {
  margin-left: -2.84e-14px;
  margin-right: -8.5px;
}

.container-653.container-655 {
  margin-left: -1.42e-14px;
  margin-right: -7.5px;
}

.container-653.container-656 {
  margin-left: -1.42e-14px;
  margin-right: -0.5px;
}
</style>
