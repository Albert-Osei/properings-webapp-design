<template>
  <div class="navbar">
      <div class="navbar-left">
          <p>Properings</p>
      </div>

      <div class="navbar-right">
          <a>Home</a>
          <a>About Us</a>
          <a>Team</a>
          <a>Contact</a>
      </div>

  </div>
</template>

<script>
export default {
    name: 'Navbar'

}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;0,800;1,400&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700&display=swap');

*, body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.navbar-left > p {
    font-family: 'Playfair Display';
    font-weight: bold;
    font-size: 48px;    
    color: #333333;
}

.navbar-right > a {
    font-family: 'Roboto';
    font-weight: bold;
    font-size: 18px;
    color: #333333;
    text-transform: uppercase;
    margin-left: 60px;

}

.navbar {
    width: 100%;
    height: 79px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 35px 250px 35px 100px;
    background: rgba(0, 0, 0, 0.26);
}

</style>