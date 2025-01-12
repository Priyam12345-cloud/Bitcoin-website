<template>
  <div :class="[`data-971-1`, className || ``]">
    <div class="link-62">
      <imgmargin :src="imgmarginProps.src" :className="imgmarginProps.className" />
      <div class="paragraph-191">
        <div class="overlap-group-84">
          <div class="bit-torrent valign-text-middle wwwcoingeckocomintersemi-bold-14">{{ bittorrent }}</div>
          <div class="btt valign-text-middle wwwcoingeckocomsemanticlink">{{ btt }}</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Imgmargin from "./Imgmargin";
export default {
  name: "Data136",
  components: {
    Imgmargin,
  },
  props: ["bittorrent", "btt", "className", "imgmarginProps"],
};
</script>

<style>
.data-971-1 {
  align-items: flex-start;
  background-color: var(--black);
  display: flex;
  flex-direction: column;
  height: 69px;
  padding: 22.5px 10px;
  position: relative;
  width: 324.05px;
}

.link-62 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  position: relative;
  width: 100%;
}

.paragraph-191 {
  height: 20px;
  position: relative;
  width: 93.17px;
}

.overlap-group-84 {
  height: 20px;
  position: relative;
  top: -2px;
  width: 94px;
}

.bit-torrent {
  color: var(--white-lilac);
  font-weight: 600;
  height: 20px;
  left: 0;
  line-height: 20px;
  position: absolute;
  top: 0;
  white-space: nowrap;
  width: 71px;
}

.btt {
  color: var(--white);
  font-weight: 500;
  height: 16px;
  left: 70px;
  line-height: 16px;
  position: absolute;
  top: 3px;
  white-space: nowrap;
  width: 23px;
}

.data-971-1.data-971 .paragraph-191 {
  width: 93.55px;
}

.data-971-1.data-971 .bit-torrent {
  width: 70px;
}

.data-971-1.data-971 .btt {
  width: 24px;
}
</style>
