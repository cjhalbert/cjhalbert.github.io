<template>
  <section class="global-section home-section"> 
    <img src="../assets/me.jpg" alt="">
  </section>
</template>

<style lang="scss" scoped>
section {
  display: flex;
  justify-content: center;
  align-items: center;
}
@media screen and (max-width: 600px) {
  section {
    padding: 0 5vw;
  }
}

img {
  width: 100%;
}
</style>