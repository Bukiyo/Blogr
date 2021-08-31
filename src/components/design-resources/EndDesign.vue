<template>
    <section class="end">
        <div class="container">
            <div class="row content">
                <div class="col-md-6 text img">
                    <img class="bg" src="@/assets/illustration-laptop-desktop.svg" alt="">
                </div>
                <div class="col-md-6 text">
                    <base-caption>
                        <template #caption >
                            <section class="caption">
                               <h4 class="sub-title">Free, open, simple</h4>
                                <p class="body first-body">
                                    Blogr is a free and open source application backed by a large
                                    community of helpful developers. It supports features such as code
                                    syntax highlighting, RSS feeds, social media integration, third-party
                                    commenting tools, and works seamlessly with Google Analytics. The
                                    architecture is clean and is relatively easy to learn.
                                </p>

                                <h4 class="sub-title">Powerful tooling</h4>
                                <p class="body">
                                    Batteries included. We built a simple and straightforward CLI tool that
                                    makes customization and deployment a breeze, but capable of 
                                    producing even the most complicated sites.
                                </p> 
                            </section>
                            

                        </template>   
                        

                    </base-caption>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import BaseCaption from '../UI/BaseCaption.vue';
export default {
    components: {BaseCaption},
    setup() {
        
    },
}
</script>

<style scoped>
    .end {
        font-family: "Overpass", sans-serif;
        margin-bottom: 8rem;
        
    }
    .title {
        margin-bottom: 5rem;
    }

    .sub-title {
        margin-bottom: 1.5rem;
    }

    .title, .sub-title {
       color: hsl(208, 49%, 24%); 
       font-weight: 600;
    }
    .body { 
        font-weight: 300;
    }

    .first-body {
        margin-bottom: 5rem;
    }

    .img .bg {
        position: relative;
        bottom: 0%;
        right: 90%;
    }
    .text {
        position: relative;
    }
    .caption {
        position: absolute;
        top: 50%;
        transform: translate(0%, -50%);
    }

     @media screen and (max-width: 1200px) {
        .img .bg {
           width: 50rem;
        }
    
    }

     @media screen and (max-width: 991.5px) {
        .img .bg {
           width: 45rem;
           position: relative;
            bottom: 0%;
            right: 130%;
        }
        .body{
            width: 23rem;
        }
    }

    @media screen and (max-width: 767.5px) {
        .img {
            display: flex;
            justify-content: center;
        }
        .img .bg {
            position: relative;
            bottom: 5%;
            left: 7%;
            width: 42rem;
            margin-bottom: 0rem;
        }
        .text {
            margin-bottom: 25rem;
        }
        .content {
            flex-direction: column;
        }
        .title {
            font-size: 2.5rem;
        }
        .sub-title {
            text-align: center;
            font-size: 2.5rem;
        }
        .body {
            text-align: center;
            font-size: 1.2rem;
            line-height: 2.5rem;
            width: auto;
        }

    }

    @media screen and (max-width: 650px) {
        .img {
            display: flex;
            justify-content: center;
        }
        .img .bg {
            position: relative;
            bottom: 5%;
            left: 7%;
            width: 32rem;
            margin-bottom: 0rem;
        }
        .text {
            margin-bottom: 25rem;
        }
        .content {
            flex-direction: column;
        }
        .title {
            font-size: 2rem;
        }
        .sub-title {
            text-align: center;
            font-size: 2rem;
        }
        .body {
            text-align: center;
            font-size: 1rem;
            line-height: 2.5rem;
            width: auto;
        }
    }


    @media screen and (max-width: 520px) {
        .img .bg {
            position: relative;
            bottom: 5%;
            left: 7%;
            width: 30rem;
            margin-bottom: 0rem;
        }
        .text {
            margin-bottom: 25rem;
        }
        .content {
            flex-direction: column;
        }
        .title {
            font-size: 2rem;
        }
        .sub-title {
            text-align: center;
            font-size: 2rem;
        }
        .body {
            text-align: center;
            font-size: 1rem;
            line-height: 2.5rem;
            width: auto;
        }

    }

    @media screen and (max-width: 460px) {
        .img .bg {
            position: relative;
            bottom: 5%;
            left: 7%;
            width: 26rem;
            margin-bottom: 0rem;
        }
        .text {
            margin-bottom: 25rem;
        }
        .content {
            flex-direction: column;
        }
        .title {
            font-size: 2rem;
        }
        .sub-title {
            text-align: center;
            font-size: 2rem;
        }
        .body {
            text-align: center;
            font-size: 1rem;
            line-height: 2.5rem;
            width: auto;
        }
    }

    @media screen and (max-width: 400px) {
       .img .bg {
            position: relative;
            bottom: 5%;
            left: 7%;
            width: 23rem;
            margin-bottom: 0rem;
        }
        .text {
            margin-bottom: 25rem;
        }
        .content {
            flex-direction: column;
        }
        .title {
            font-size: 1.85rem;
        }
        .sub-title {
            text-align: center;
            font-size: 1.85rem;
        }
        .body {
            text-align: center;
            font-size: 1rem;
            line-height: 2.5rem;
            width: auto;
        }
    }

    @media screen and (max-width: 350px) {
        .img .bg {
            position: relative;
            bottom: 5%;
            left: 7%;
            width: 21rem;
            margin-bottom: 0rem;
        }
        .text {
            margin-bottom: 25rem;
        }
        .content {
            flex-direction: column;
        }
        .title {
            font-size: 1.75rem;
        }
        .sub-title {
            text-align: center;
            font-size: 1.75rem;
        }
        .body {
            text-align: center;
            font-size: 1rem;
            line-height: 2.5rem;
            width: auto;
        }
    }

    @media screen and (max-width: 315px) {
       .img .bg {
            position: relative;
            bottom: 5%;
            left: 7%;
            width: 18rem;
            margin-bottom: 2rem;
        }
        .text {
            margin-bottom: 25rem;
        }
        .content {
            flex-direction: column;
        }
        .title {
            font-size: 1.65rem;
        }
        .sub-title {
            text-align: center;
            font-size: 1.65rem;
        }
        .body {
            text-align: center;
            font-size: 0.9rem;
            line-height: 2.5rem;
            width: auto;
        }
    }

</style>