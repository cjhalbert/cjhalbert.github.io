<template>
  <section class="global-section">
    <h1 class="project-title">Maxwell Denari</h1>
    <h2>Branding, Visual Design</h2>
    <p class="project-description">Maxwell Denari is a freelance writer and photographer who has an immense passion for music and storytelling. Maxwell reached out to me to design a logo for his personal brand so we started working together. Over the course of a few ideas, revisions, and redesigns, we eventually came to a logo that he and I were both excited about.</p>

    <h2 class="section-title">First Round of Designs</h2>
    <div class="project-grid project-page">
        <div><img src="../assets/maxwell/maxwell-ideas1.svg" alt=""></div>
        <div><img src="../assets/maxwell/maxwell-ideas2.svg" alt=""></div>
        <div><img src="../assets/maxwell/maxwell-ideas3.svg" alt=""></div>
        <div><img src="../assets/maxwell/maxwell-ideas4.svg" alt=""></div>
        <div><img src="../assets/maxwell/maxwell-ideas5.svg" alt=""></div>
    </div>
    
    <h2 class="section-title">Final Options</h2>
    <div class="project-grid oneCol project-page">
        <div><img src="../assets/maxwell/max-mockup1.svg" alt=""></div>
        <div><img src="../assets/maxwell/max-mockup2.svg" alt=""></div>
        <div><img src="../assets/maxwell/max-mockup3.svg" alt=""></div>
        <div><img src="../assets/maxwell/max-mockup4.svg" alt=""></div>
    </div>

    <h2 class="section-title">Final Design</h2>
    <div class="project-grid oneCol project-page">
        <div><img src="../assets/maxwell/max-final-vert.svg" alt=""></div>
    </div>
     <hr>
    <div class="next-project-section">
      <h1 class="next-project-link"><router-link to="/whocares">Whocares</router-link></h1>
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
  margin: 10vh 0;
}

.section-title {
  margin-top: 10vh;
}

.oneCol {
  grid-template-columns: 1fr;

  div {
    width: 50%;
  }
}
</style>