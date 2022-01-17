<template>
  <div id="main-wrapper pt-0">
    <Nav />
    <div>
      <Intro />
      <!-- <Example /> -->
      <Market />
      <Features />
      <Join />
      <Say />
      <Question />
    </div>
    <Footer />

    <CookieAlert />
  </div>
</template>

<script>
// @ is an alias to /src
import Nav from "../components/landing/Nav";
import Intro from "../components/landing/Intro";
// import Example from "../components/FormError";

export default {
  name: "LandingPage",
  components: {
    Nav,
    Intro,
    // Example,
  },
};
</script>
