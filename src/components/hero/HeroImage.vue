<template>
  <div class="wrapper"></div>
  <div class="overlay"></div>
  <div class="container">
    <div class="leader">
      <slot></slot>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.wrapper {
  position: absolute;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  background-image: url(../../assets/background.jpg);
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  background: rgba(0, 29, 61, 0.45);
}

.container {
  position: absolute;
  width: 100vw;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
