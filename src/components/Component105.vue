<template>
  <article class="component-10-5">
    <div class="container-663">
      <div class="container-664">
        <div class="container-665">
          <div class="symbol valign-text-middle fontawesome5brands-regular-normal-white-12px">{{ symbol }}</div>
        </div>
        <div class="twitter valign-text-middle wwwcoingeckocomintersemi-bold-12">{{ twitter }}</div>
      </div>
    </div>
  </article>
</template>

<script>
export default {
  name: "Component105",
  props: ["symbol", "twitter"],
};
</script>

<style>
.component-10-5 {
  align-items: center;
  background-color: var(--ebony);
  border-radius: 8px;
  display: inline-flex;
  flex: 0 0 auto;
  justify-content: center;
  padding: 6px 10px;
  position: relative;
}

.container-663 {
  align-items: flex-start;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.container-664 {
  align-items: center;
  align-self: stretch;
  display: flex;
  flex: 0 0 auto;
  gap: 4px;
  position: relative;
  width: 100%;
}

.container-665 {
  align-items: flex-end;
  display: inline-flex;
  flex: 0 0 auto;
  flex-direction: column;
  position: relative;
}

.symbol {
  letter-spacing: 0;
  line-height: 12px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}

.twitter {
  color: var(--dhancowhite);
  font-weight: 600;
  line-height: 16px;
  margin-top: -1px;
  position: relative;
  text-align: right;
  white-space: nowrap;
  width: fit-content;
}
</style>
