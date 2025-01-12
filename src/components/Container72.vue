<template>
  <div class="container-500">
    <container52
      :percent="container5Props.percent"
      :className="container5Props.className"
      :container62Props="container5Props.container62Props"
    />
  </div>
</template>

<script>
import Container52 from "./Container52";
export default {
  name: "Container72",
  components: {
    Container52,
  },
  props: ["container5Props"],
};
</script>

<style>
.container-500,
.container-501 {
  align-items: center;
  align-self: stretch;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: flex-end;
  max-width: 200.34px;
  padding: 1.5px 0px 2px;
  position: relative;
}
</style>
