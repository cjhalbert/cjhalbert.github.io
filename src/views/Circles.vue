<template>
  <section class="global-section">
    <h1 class="project-title">Circles</h1>
    <h2>Illustration, Visual Design</h2>
    <p class="project-description">This project was a visual design excercise for me to explore some digital illustrations a little outside my comfort zone. For two weeks I gave myself the challenge of using Adobe Illustrator to create some unique circular forms using only lines. This was a ton of fun to do and definitely pushed me out of comfort zone!</p>
    <div class="project-grid project-page">
      <div><img src="../assets/circles/circle1.png" alt=""></div>
      <div><img src="../assets/circles/circle2.png" alt=""></div>
      <div><img src="../assets/circles/circle3.png" alt=""></div>
      <div><img src="../assets/circles/circle4.png" alt=""></div>
      <div><img src="../assets/circles/circle5.png" alt=""></div>
      <div><img src="../assets/circles/circle6.png" alt=""></div>
      <div><img src="../assets/circles/circle7.png" alt=""></div>
      <div><img src="../assets/circles/circle8.png" alt=""></div>
      <div><img src="../assets/circles/circle9.png" alt=""></div>
      <div><img src="../assets/circles/circle10.png" alt=""></div>
      <div><img src="../assets/circles/circle11.png" alt=""></div>
      <div><img src="../assets/circles/circle12.png" alt=""></div>
      <div><img src="../assets/circles/circle13.png" alt=""></div>
      <div><img src="../assets/circles/circle14.png" alt=""></div>
      <div><img src="../assets/circles/circle15.png" alt=""></div>
      <div><img src="../assets/circles/circle16.png" alt=""></div>
      <div><img src="../assets/circles/circle17.png" alt=""></div>
      <div><img src="../assets/circles/circle18.png" alt=""></div>
    </div>
    <hr>
    <div class="next-project-section">
      <h1 class="next-project-link"><router-link to="/maxwell">Maxwell Denari</router-link></h1>
    </div>
  </section>
</template>

<style lang="scss" scoped>
section {
  padding-top: 15vh;  
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: column;
  font-family: "Orpheus Pro", serif;
}

img {
  width: 100%;
}

h2 {
  font-style: italic;
  margin: 0;
}

p {
  font-family: "Neue Haas Grotesk Text Pro", sans-serif;
  color: #6A6B6B;
  font-weight: 400;
  font-size: 16px;
  line-height: 35px;
  width: 50vw;
  margin-top: 1vh;
}

@media screen and (max-width: 600px) {
  p {
    margin-top: 1vh;
    width: 100%;
  }
}

.project-page {
  margin-top: 1vh;
}
</style>