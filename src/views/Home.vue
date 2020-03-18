<template>
  <div class="home">
    <h1 id="header">Welcome to Conservation Worldwide</h1>
    <img id="welcomeimage" src="/images/welcome.jpg">
    <div class="about">
      <h2>About Us</h2>
      <p class="para">Conservation Worldwide is dedicated to preserving the wondrous animals that roam our planet.
       Through the actions of our generous donors and volunteers, we constantly strive toward a
       future where humans and animals can co-exist without danger of extinction. Browse our website to see
       all of the animals that we help conserve and visit the "How You Can Help" page to learn what you can do to help us.</p>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
  }
}
</script>

<style scoped>

.para {
  margin: auto;
  align-items: center;
  box-sizing: border-box;
  font-size: 1.3em;
  margin-bottom: 2%;
}

#welcomeimage {
  box-sizing: border-box;
  height: 22%;
  width: 45%;
  margin-bottom: 1.2%;
  margin-top: .5%;
}

#header {
  margin-top: 1%;
}

.about {
  background-color: #b7ebc9;
  width: 45.1%;
  margin: auto;
}
</style>
