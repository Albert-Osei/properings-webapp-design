<template>
  <div class="home">
    <div class="section-one">
      <Navbar />
      <p class="section1-text">New Way of Living</p>
      <button class="section1-btn">Get Started</button>
    </div>

    <!-- About section -->
    <section id="about">
      <div class="about-image">
        <img src="../assets/Rectangle17.png" alt="" />
      </div>
      <div class="about-text">
        <p class="about-text-header">About Us</p>
        <p class="about-text-content">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Dolor turpis
          aliquam urna et, aliquam sed dignissim fermentum urna .Potenti sit
          sagittis dui netus facilisi. Lacinia tincidunt ac feugiat sed.
          Fermentum mattis egestas at sed eu nibh.
        </p>
        <button class="about-btn">Learn more</button>
      </div>
    </section>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Home",
  components: {
    Navbar,
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;1,400&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;0,800;1,400&display=swap");

body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.section-one {
  background-image: url(../assets/Rectangle16.png);
  height: 969px;
  width: 100%;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  margin-bottom: 182px;
}

.section1-text {
  font-family: "Playfair Display";
  font-weight: bold;
  font-size: 96px;
  color: #333333;
  width: 400px;
  margin: 96px 0 35px 100px;
}

.section1-btn {
  width: 257px;
  height: 64px;
  background: #222222;
  font-family: "Poppins";
  font-weight: bold;
  font-size: 24px;
  color: #e0e0e0;
  border: none;
  margin: 65px 0 0 100px;
}

.about-image {
  width: 700px;
  height: 676px;
}
.about-image img {
  width: 100%;
  height: 100%;
}

.about-text {
  width: 600px;
}
.about-text-header {
  font-family: 'Playfair Display';
  font-weight: bold;
  font-size: 64px;
  color: #333333;
  text-align: center;
}
.about-text-content {
  font-family: 'Poppins';
  font-weight: normal;
  font-size: 24px;
  color: #000000;
}
.about-btn {
  width: 260px;
  height: 64px;
  background: #222222;
  font-family: 'Poppins';
  font-weight: bold;
  font-size: 24px;
  color: #E0E0E0;
  margin-top: 114px;
}

#about {
  display: flex;
  justify-content: center;
  margin-bottom: 340px;
}

#about div:last-of-type {
  margin-left: 65px;
}













</style>
