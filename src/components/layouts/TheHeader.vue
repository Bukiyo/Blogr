<template>
  <header class="text-center">
    <!-- <img class='header-img' src="@/assets/bg-pattern-intro.svg" alt=""> -->
    <the-navbar></the-navbar>
    <div class="heading-items">
      <h1>A modern publishing platform</h1>
      <p>Grow your audience and build your online brand</p>
      <button class="btn my-2 my-sm-0 btnStart" type="submit">
        Start for Free
      </button>
      <button class="btn ml-2 my-sm-0 btnLearn" type="submit">
        Learn More
      </button>
    </div>
  </header>
</template>

<script>
import TheNavbar from "./TheNavbar.vue";
export default {
  components: { TheNavbar },
  data() {},
};
</script>

<style scoped>

/* @media screen and (min-width: 1440px) { */
  header {
  background: url("../../assets/bg-pattern-intro.svg") 22% 51.5% no-repeat,
    linear-gradient(to right, hsl(13, 100%, 72%), hsl(353, 100%, 62%));
  /* background-image: url("../../assets/bg-pattern-intro.svg"); */
  /* background-repeat: no-repeat; */
  border-bottom-left-radius: 80px;
  position: relative;
  min-height: 40rem;
  overflow: hidden;
  color: white;
  margin-bottom: 8rem;
}

.heading-items {
  /* position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%); */
  justify-content: center;
  padding: 10rem 7rem 0rem 7rem;
}

h1 {
  font-family: "Overpass", sans-serif;
  font-weight: 600;
  font-size: 3.5rem;
}

p {
  font-family: "Overpass", sans-serif;
  font-weight: 300;
}

.heading-items button {
  border-radius: 25px;
  width: 8rem;
}

.btnStart {
  background-color: white;
  color: hsl(356, 100%, 66%);
  font-weight: bold;
}

.btnStart:hover {
  background-color: hsl(355, 100%, 74%);
  color: white;
}

.btnLearn {
  color: white;
  border: 1px solid white;
}

.btnLearn:hover {
  background-color: white;
  color: hsl(356, 100%, 66%);
  font-weight: bold;
}

@media screen and (max-width: 767px) {
  .heading-items h1 {
    font-family: "Overpass", sans-serif;
    font-weight: 600;
    font-size: 2.5rem;

  }
}

@media screen and (max-width: 575px) {
  .heading-items h1 {
    font-family: "Overpass", sans-serif;
    font-weight: 600;
    font-size: 3rem;

  }

  .heading-items {
  padding: 4rem 2rem 4rem 2rem;

  }

  header {
    min-height: 35rem
  }
}

@media screen and (max-width: 485px) {
  .heading-items h1 {
    font-family: "Overpass", sans-serif;
    font-weight: 600;
    font-size: 2.5rem;

  }

  .heading-items {
  padding: 4rem 2rem 4rem 2rem;

  }

  header {
    min-height: 35rem
  }
}

@media screen and (max-width: 415px) {
  .heading-items h1 {
    font-family: "Overpass", sans-serif;
    font-weight: 600;
    font-size: 2.25rem;

  }

  .heading-items {
  padding: 5rem 2rem 4rem 2rem;

  }

  header {
    min-height: 35rem
  }
}

@media screen and (max-width: 380px) {
  .heading-items h1 {
    font-family: "Overpass", sans-serif;
    font-weight: 600;
    font-size: 2rem;

  }

  .heading-items {
  padding: 5rem 2rem 4rem 2rem;

  }

  header {
    min-height: 35rem
  }
}

@media screen and (max-width: 345px) {
  .heading-items h1 {
    font-family: "Overpass", sans-serif;
    font-weight: 600;
    font-size: 1.75rem;

  }

  .heading-items {
  padding: 5rem 2rem 4rem 2rem;

  }

  header {
    min-height: 35rem
  }
}

@media screen and (max-width: 309px) {
  .heading-items h1 {
    font-family: "Overpass", sans-serif;
    font-weight: 600;
    font-size: 1.5rem;

  }

  .heading-items {
  padding: 5rem 2rem 4rem 2rem;

  }

  header {
    min-height: 35rem
  }
}

/* } */


/* .header-img {
     position: absolute;
     top: -75rem;
     width: 190rem;
     right: -71rem;
    } */
</style>