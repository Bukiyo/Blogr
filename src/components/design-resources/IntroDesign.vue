<template>
    <section class="intro">
        <h2 class="text-center title">Designed for the future</h2>
        <div class="container">
            <div class="row content">
                <div class="col-md-6 text">
                    <base-caption>
                        <template #caption>
                            <h4 class="sub-title">Introducing an extensible editor</h4>
                            <p class="body first-body">
                                Blogr features an exceedingly intuitive interface which lets you focus 
                                on one thing: creating content. The editor supports management of 
                                 multiple blogs and allows easy manipulation of embeds such as images, 
                                  videos, and Markdown. Extensibility with plugins and themes provide  
                                  easy ways to add functionality or change the looks of a blog.
                            </p>

                            <h4 class="sub-title">Robust content management</h4>
                            <p class="body">
                                Flexible content management enables users to easily move through
                                posts. Increase the usability of your blog by adding customized
                                categories, sections, format, or flow. With this functionality, you're in
                                full control.
                            </p>

                        </template>   
                        

                    </base-caption>
                </div>
                <div class="col-md-6 img">
                    <img class="bg" src="@/assets/illustration-editor-desktop.svg" alt="">
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
    .intro {
        font-family: "Overpass", sans-serif;
        
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
        line-height: 2.5rem;
    }

    .first-body {
        margin-bottom: 5rem;
    }

    .img .bg {
        position: relative;
        bottom: 20%;
        right: -20%;
    }

    @media screen and (max-width: 1200px) {
        .img .bg {
            position: relative;
            bottom: 20%;
            right: -33%;
            width: 45rem;
        }
        .body {
            line-height: 2.5rem;
        }
    }

     @media screen and (max-width: 992px) {
        .img .bg {
            position: relative;
            bottom: 5%;
            right: -25%;
            width: 40rem
        }
        .text {
            margin-bottom: 10rem;
        }
        .body {
            line-height: 2.5rem;
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
            right: 0;
            width: 40rem;
            margin-bottom: 3rem;
        }
        .text {
            margin-bottom: 10rem;
        }
        .content {
            flex-direction: column-reverse;
        }
        .title {
            font-size: 2.25rem;
        }
        .sub-title {
            text-align: center;
            font-size: 2.25rem;
        }
        .body {
            text-align: center;
            font-size: 1rem;
            line-height: 2.5rem;
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
            right: 0;
            width: 32rem;
            margin-bottom: 3rem;

        }
        .text {
            margin-bottom: 10rem;
        }
        .content {
            flex-direction: column-reverse;
        }
        .title {
            font-size: 2.25rem;
        }
        .sub-title {
            text-align: center;
            font-size: 2.25rem;
        }
        .body {
            text-align: center;
            font-size: 1rem;
            line-height: 2.5rem;
        }
    }

    @media screen and (max-width: 520px) {
        .img {
            display: flex;
            justify-content: center;
        }
        .img .bg {
            position: relative;
            bottom: 5%;
            right: 0;
            width: 28rem;
            margin-bottom: 3rem;

        }
        .text {
            margin-bottom: 10rem;
        }
        .content {
            flex-direction: column-reverse;
        }
        .title {
            font-size: 2.25rem;
        }
        .sub-title {
            text-align: center;
            font-size: 2.25rem;
        }
        .body {
            text-align: center;
            font-size: 1rem;
            line-height: 2.5rem;
        }
    }

    @media screen and (max-width: 450px) {
        .img {
            display: flex;
            justify-content: center;
        }
        .img .bg {
            position: relative;
            bottom: 5%;
            right: 0;
            width: 24rem;
            margin-bottom: 3rem;

        }
        .text {
            margin-bottom: 10rem;
        }
        .content {
            flex-direction: column-reverse;
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
            font-size: 1.1rem;
            line-height: 2.5rem;
        }
    }

    @media screen and (max-width: 390px) {
        .img {
            display: flex;
            justify-content: center;
        }
        .img .bg {
            position: relative;
            bottom: 5%;
            right: 0;
            width: 21rem;
            margin-bottom: 3rem;

        }
        .text {
            margin-bottom: 10rem;
        }
        .content {
            flex-direction: column-reverse;
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
        }
    }

    @media screen and (max-width: 340px) {
        .img {
            display: flex;
            justify-content: center;
        }
        .img .bg {
            position: relative;
            bottom: 5%;
            right: 0;
            width: 19rem;
            margin-bottom: 3rem;

        }
        .text {
            margin-bottom: 10rem;
        }
        .content {
            flex-direction: column-reverse;
        }
        .title {
            font-size: 1.9rem;
        }
        .sub-title {
            text-align: center;
            font-size: 1.9rem;
        }
        .body {
            text-align: center;
            font-size: 1rem;
            line-height: 2.5rem;
        }
    }

    @media screen and (max-width: 315px) {
        .img {
            display: flex;
            justify-content: center;
        }
        .img .bg {
            position: relative;
            bottom: 5%;
            right: 0;
            width: 16rem;
            margin-bottom: 3rem;

        }
        .text {
            margin-bottom: 10rem;
        }
        .content {
            flex-direction: column-reverse;
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
            font-size: 0.9rem;
            line-height: 2.5rem;
        }
    }

</style>