<script setup lang="ts">
</script>

<template>
  <div style="height: 1440px; width: 2560px; background-color: white;">
    <div class="top-bar">
      <div class="left-parallelogram">
        <img src="https://i.imgur.com/Iint1M0.png" style="width: 120px; position: absolute; left: 30%; top: 30%;" />
      </div>
      <!-- <div class="right-parallelogram" /> -->
    </div>
  </div>
</template>

<style scoped>
.top-bar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 40px;
  background-color: rgb(42, 42, 42);
  z-index: 100;
  box-shadow: 0 10px 2px -2px gray;
}

.left-parallelogram {
  position: absolute;
  left: -20px;
  top: 0;
  width: 250px;
  height: 100px;
  background-color: rgb(26, 26, 26);
  transform: skew(-20deg);
  box-shadow: 0 10px 2px -2px gray;
}

.right-parallelogram {
  position: absolute;
  right: -20px;
  top: 0;
  width: 200px;
  height: 75px;
  background-color: black;
  transform: skew(20deg);
}
</style>
