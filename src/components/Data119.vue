<template>
  <div class="data-917">
    <container222 :className="container222Props.className" />
    <div class="percent-73 valign-text-middle taviraj-semi-bold-red-orange-14px">12.3%</div>
  </div>
</template>

<script>
import Container222 from "./Container222";
export default {
  name: "Data119",
  components: {
    Container222,
  },
  props: ["container222Props"],
};
</script>

<style>
.data-917 {
  align-items: center;
  background-color: var(--black);
  display: flex;
  gap: 4.37px;
  height: 69px;
  padding: 24px 10px 25px 19.63px;
  position: relative;
  width: 83.05px;
}

.percent-73 {
  letter-spacing: 0;
  line-height: 20px;
  margin-right: -2.7px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
