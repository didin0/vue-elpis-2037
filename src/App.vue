<template>
  <div class="banner">
    <video autoplay loop muted>
      <source src="../public/bande-annonce.mp4" type="video/mp4">
    </video>
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
body {
  margin: 0;
  padding: 0;
}

.banner {
  width: 100%;
  height: 100vh;
  overflow: hidden;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: url('../public/cursor.png'), auto;

}

.banner video {
  position: absolute;
  top: 0;
  left: 0;
  object-fit: cover;
  width: 100%;
  height: 100%;
}


</style>
