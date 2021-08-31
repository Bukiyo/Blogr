<template>
  <section class="art-infrastructure">
    <div class="container">
      <!-- <div class="row content">
            <div class="col-md-6 position-relative">
                <img class="img" src="@/assets/illustration-phones.svg" alt="">
            </div>

            <div class="col-md-6 text">
                <h2 class="title">State of the Art Infrastructure</h2>
                <p class="sub-title">
                    With reliability and speed in mind, worldwide data centers provide
                    the
                    backbone for ultra-fast connectivity. This ensures your site will
                    load
                    instantly, no matter where your readers are, keeping your site
                    competitive.
                </p>
            </div>
      </div> -->
      <div class="content">
        <div>
          <img class="img" src="@/assets/illustration-phones.svg" alt="" />
        </div>

        <div class="text">
          <h2 class="title">State of the Art Infrastructure</h2>
          <p class="sub-title">
            With reliability and speed in mind, worldwide data centers provide
            the backbone for ultra-fast connectivity. This ensures your site
            will load instantly, no matter where your readers are, keeping your
            site competitive.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  setup() {},
};
</script>

<style scoped>
.title {
  margin-bottom: 2rem;
  font-weight: 600;
}
.sub-title {
  font-weight: 300;
  font-size: 1.1rem;
}
/* .row {
    position: relative;
} */
.text {
  font-family: "Overpass", sans-serif;
  color: white;
  margin-top: 8rem;
  padding: 3rem;
}

.art-infrastructure {
  background-color: hsl(240, 10%, 16%);
  background: url("../../assets/bg-pattern-circles.svg") -38% 78% no-repeat,
    linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
  height: 30rem;
  border-top-right-radius: 80px;
  border-bottom-left-radius: 80px;
  margin-bottom: 7rem;
}

.content {
  display: flex;
  justify-content: flex-start;
}

/* .img {
  position: absolute;
  top: -25%;
} */

@media screen and (max-width: 1280px) {
  /* .img {
    position: absolute;
    top: -25%;
    left: 0%;
  } */
  .content {
    display: flex;
    justify-content: flex-start;
  }
  .text {
    padding: 3rem;
  }
}

@media screen and (max-width: 1200px) {
  /* .img {
    position: absolute;
    top: -25%;
    left: -10%;
    width: 30rem;
  } */
  .img {
    width: 33rem;
  }
  .content {
    display: flex;
    justify-content: center;
  }
  .text {
    padding: 3rem;
  }
  .title {
    width: 27rem;
  }
  .sub-title {
    font-size: 1.1rem;
    width: 28rem;
  }
}

@media screen and (max-width: 1024px) {
  .img {
    width: 33rem;
  }
  .content {
    display: flex;
    justify-content: center;
  }
  /* .text {
    padding: 1rem;
  }
  .title {
    font-size: 1.2rem;
    width: 21rem;
  }
  .sub-title {
    width: 20rem;
  } */
  .text {
    padding: 3rem;
  }
  .title {
    width: 27rem;
  }
  .sub-title {
    font-size: 1.1rem;
    width: 26rem;
  }
}

@media screen and (max-width: 992px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") -38% 78% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 28rem;
    margin-bottom: 7rem;
  }
  .img {
    position: relative;
    top: 5%;
    width: 30rem;
  }

  /* .content {
      display: flex;
      flex-direction: column-reverse;
    } */

  .content {
    display: flex;
    justify-content: center;
  }
  .text {
    padding: 2rem;
  }
  .title {
    font-size: 2rem;
    width: 27rem;
  }
  .sub-title {
    font-size: 1.1rem;
    width: 26rem;
  }
}

@media screen and (max-width: 920px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") -38% 78% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 28rem;
    margin-bottom: 7rem;
  }
  .img {
    position: relative;
    top: 10%;
    width: 28rem;
  }

  /* .content {
      display: flex;
      flex-direction: column-reverse;
    } */

  .content {
    display: flex;
    justify-content: center;
  }
  .text {
    padding: 2rem;
  }
  .title {
    font-size: 1.85rem;
    width: 27rem;
  }
  .sub-title {
    font-size: 1.1rem;
    width: 26rem;
  }
}

@media screen and (max-width: 900px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") -38% 78% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 28rem;
    margin-bottom: 7rem;
  }
  .img {
    position: relative;
    top: 20%;
    width: 25rem;
  }

  .content {
    display: flex;
    justify-content: center;
  }
  .text {
    padding: 2rem;
  }
  .title {
    font-size: 1.8rem;
    width: 27rem;
  }
  .sub-title {
    font-size: 1.1rem;
    width: 26rem;
  }
}

@media screen and (max-width: 850px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") -38% 78% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 23rem;
    margin-bottom: 7rem;
  }
  .img {
    position: relative;
    top: 15%;
    width: 22rem;
    right: 7%;
    
  }

  .content {
    display: flex;
    justify-content: center;
  }
  .text {
    padding: 0rem;
  }
  .title {
    font-size: 1.8rem;
    width: 27rem;
  }
  .sub-title {
    font-size: 1rem;
    width: 26rem;
  }
}

@media screen and (max-width: 800px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") -38% 78% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 21rem;
    margin-bottom: 7rem;
  }
  .img {
    position: relative;
    top: 15%;
    width: 20rem;
    right: 0%;
    
  }

  .content {
    display: flex;
    justify-content: center;
  }
  .text {
    padding: 0rem;
    margin-top: 6rem;
  }
  .title {
    font-size: 1.8rem;
    width: 27rem;
  }
  .sub-title {
    font-size: 1rem;
    width: 26rem;
  }
}

@media screen and (max-width: 767.5px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") 38% 125% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 45rem;
    border-top-right-radius: 80px;
    border-bottom-left-radius: 80px;
    margin-bottom: 7rem;
  }
  .content {
    display: flex;
    flex-direction: column;
    position: relative;
    bottom: 10rem;
    margin-top: 5rem;
  }
  .img {
    width: 30rem;
    padding: 0 3rem;
    
  }
  .text {
    padding: 0 2rem;
    margin-top: 3rem;
  }
  .title {
    text-align: center;
    font-size: 2.5rem;

  }
  .sub-title {
    text-align: center;
    font-size: 1.1rem;
    line-height: 2rem;
  }
}

@media screen and (max-width: 500px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") 38% 125% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 48rem;
    border-top-right-radius: 80px;
    border-bottom-left-radius: 80px;
    margin-bottom: 7rem;
  }
  .content {
    display: flex;
    flex-direction: column;
    position: relative;
    bottom: 10rem;
    margin-top: 5rem;
  }
  .img {
    width: 26rem;
    padding: 0 3rem;
    position: relative;
    right: 0%;
  }
  .text {
    padding: 0 3rem;
    margin-top: 3rem;
  }
  .title {
    text-align: center;
    font-size: 2.1rem;
    width: auto;
  }
  .sub-title {
    text-align: center;
    font-size: 1rem;
    width: auto;
    line-height: 2rem;
  }
}

@media screen and (max-width: 450px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") 38% 125% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 48rem;
    border-top-right-radius: 80px;
    border-bottom-left-radius: 80px;
    margin-bottom: 7rem;
  }
  .content {
    display: flex;
    flex-direction: column;
    position: relative;
    bottom: 10rem;
    margin-top: 5rem;
  }
  .img {
    width: 26rem;
    padding: 0 3rem;
    position: relative;
    right: 3%;
  }
  .text {
    padding: 0 3rem;
    margin-top: 3rem;
  }
  .title {
    text-align: center;
    font-size: 2.1rem;
    width: auto;
  }
  .sub-title {
    text-align: center;
    font-size: 1rem;
    width: auto;
    line-height: 2rem;
  }
}

@media screen and (max-width: 380px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") 38% 125% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 50rem;
    border-top-right-radius: 80px;
    border-bottom-left-radius: 80px;
    margin-bottom: 7rem;
  }
  .content {
    display: flex;
    flex-direction: column;
    position: relative;
    bottom: 10rem;
    margin-top: 5rem;
  }
  .img {
    width: 26rem;
    padding: 0 3rem;
    position: relative;
    right: 15%;
    
  }
  .text {
    padding: 0 3rem;
    margin-top: 2rem;
  }
  .title {
    text-align: center;
    font-size: 2rem;
    width: auto;
  }
  .sub-title {
    text-align: center;
    font-size: 1rem;
    width: auto;
    line-height: 2rem;
  }
}

@media screen and (max-width: 350px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") 38% 125% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 50rem;
    border-top-right-radius: 80px;
    border-bottom-left-radius: 80px;
    margin-bottom: 7rem;
  }
  .content {
    display: flex;
    flex-direction: column;
    position: relative;
    bottom: 10rem;
    margin-top: 5rem;
  }
  .img {
    width: 24rem;
    padding: 0 3rem;
    position: relative;
    right: 15%;
    
  }
  .text {
    padding: 0 3rem;
    margin-top: 2rem;
  }
  .title {
    text-align: center;
    font-size: 1.9rem;
    width: auto;
  }
  .sub-title {
    text-align: center;
    font-size: 1rem;
    width: auto;
    line-height: 2rem;
  }
}

@media screen and (max-width: 340px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") 38% 125% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 50rem;
    border-top-right-radius: 80px;
    border-bottom-left-radius: 80px;
    margin-bottom: 7rem;
  }
  .content {
    display: flex;
    flex-direction: column;
    position: relative;
    bottom: 10rem;
    margin-top: 5rem;
  }
  .img {
    width: 24rem;
    padding: 0 3rem;
    position: relative;
    right: 15%;
    
  }
  .text {
    padding: 0 3rem;
    margin-top: 2rem;
  }
  .title {
    text-align: center;
    font-size: 1.7rem;
    width: auto;
  }
  .sub-title {
    text-align: center;
    font-size: 1rem;
    width: auto;
    line-height: 2rem;
  }
}

@media screen and (max-width: 320px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") 38% 125% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 50rem;
    border-top-right-radius: 80px;
    border-bottom-left-radius: 80px;
    margin-bottom: 7rem;
  }
  .content {
    display: flex;
    flex-direction: column;
    position: relative;
    bottom: 10rem;
    margin-top: 5rem;
  }
  .img {
    width: 22rem;
    padding: 0 3rem;
    position: relative;
    right: 15%;
    
  }
  .text {
    padding: 0 3rem;
    margin-top: 2rem;
  }
  .title {
    text-align: center;
    font-size: 1.5rem;
    width: auto;
  }
  .sub-title {
    text-align: center;
    font-size: 0.85rem;
    width: auto;
    line-height: 2rem;
  }
}

@media screen and (max-width: 280px) {
  .art-infrastructure {
    background-color: hsl(240, 10%, 16%);
    background: url("../../assets/bg-pattern-circles.svg") 38% 125% no-repeat,
      linear-gradient(to right, hsl(237, 17%, 21%), hsl(237, 23%, 32%));
    height: 50rem;
    border-top-right-radius: 80px;
    border-bottom-left-radius: 80px;
    margin-bottom: 7rem;
  }
  .content {
    display: flex;
    flex-direction: column;
    position: relative;
    bottom: 10rem;
    margin-top: 5rem;
  }
  .img {
    width: 20rem;
    padding: 0 3rem;
    position: relative;
    right: 15%;
    
  }
  .text {
    padding: 0 3rem;
    margin-top: 2rem;
  }
  .title {
    text-align: center;
    font-size: 1.5rem;
    width: auto;
  }
  .sub-title {
    text-align: center;
    font-size: 0.85rem;
    width: auto;
    line-height: 2rem;
  }
}


</style>