<script setup>
import {ref, onMounted} from 'vue'


onMounted(() => {

})


</script>


<template>
    <section class="hero-section">
        <div class="responsive-container">
            <div class="fashion-industry-heading">
                <h1>The Fashion Industry through a Lens</h1>
            </div>
        </div>
    </section>
    <section class="images-link">
        <div class="responsive-container">
            <div class="images-link-wrapper">
                <div class="wave-item">
                    <img src="~/assets/images/portfolio-image.png" alt="Portfolio" class="wave-image img-fluid">
                    <a href="#" class="wave-link">View Portfolio
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                            <path
                                d="M320 0c-17.7 0-32 14.3-32 32s14.3 32 32 32l82.7 0L201.4 265.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0L448 109.3l0 82.7c0 17.7 14.3 32 32 32s32-14.3 32-32l0-160c0-17.7-14.3-32-32-32L320 0zM80 32C35.8 32 0 67.8 0 112L0 432c0 44.2 35.8 80 80 80l320 0c44.2 0 80-35.8 80-80l0-112c0-17.7-14.3-32-32-32s-32 14.3-32 32l0 112c0 8.8-7.2 16-16 16L80 448c-8.8 0-16-7.2-16-16l0-320c0-8.8 7.2-16 16-16l112 0c17.7 0 32-14.3 32-32s-14.3-32-32-32L80 32z"/>
                        </svg>
                    </a>
                </div>

                <div class="wave-item">
                    <img src="~/assets/images/services.png" alt="Biography" class="wave-image img-fluid">
                    <a href="#" class="wave-link">Biography
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                            <path
                                d="M320 0c-17.7 0-32 14.3-32 32s14.3 32 32 32l82.7 0L201.4 265.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0L448 109.3l0 82.7c0 17.7 14.3 32 32 32s32-14.3 32-32l0-160c0-17.7-14.3-32-32-32L320 0zM80 32C35.8 32 0 67.8 0 112L0 432c0 44.2 35.8 80 80 80l320 0c44.2 0 80-35.8 80-80l0-112c0-17.7-14.3-32-32-32s-32 14.3-32 32l0 112c0 8.8-7.2 16-16 16L80 448c-8.8 0-16-7.2-16-16l0-320c0-8.8 7.2-16 16-16l112 0c17.7 0 32-14.3 32-32s-14.3-32-32-32L80 32z"/>
                        </svg>
                    </a>
                </div>
                <div class="wave-item">
                    <img src="~/assets/images/biography.png" alt="Services" class="wave-image img-fluid">
                    <a href="#" class="wave-link">Our Services
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                            <path
                                d="M320 0c-17.7 0-32 14.3-32 32s14.3 32 32 32l82.7 0L201.4 265.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0L448 109.3l0 82.7c0 17.7 14.3 32 32 32s32-14.3 32-32l0-160c0-17.7-14.3-32-32-32L320 0zM80 32C35.8 32 0 67.8 0 112L0 432c0 44.2 35.8 80 80 80l320 0c44.2 0 80-35.8 80-80l0-112c0-17.7-14.3-32-32-32s-32 14.3-32 32l0 112c0 8.8-7.2 16-16 16L80 448c-8.8 0-16-7.2-16-16l0-320c0-8.8 7.2-16 16-16l112 0c17.7 0 32-14.3 32-32s-14.3-32-32-32L80 32z"/>
                        </svg>
                    </a>
                </div>
                <div class="wave-item">
                    <img src="~/assets/images/contact.png" alt="Contact" class="wave-image img-fluid">
                    <a href="#" class="wave-link">Contact Us
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                            <path
                                d="M320 0c-17.7 0-32 14.3-32 32s14.3 32 32 32l82.7 0L201.4 265.4c-12.5 12.5-12.5 32.8 0 45.3s32.8 12.5 45.3 0L448 109.3l0 82.7c0 17.7 14.3 32 32 32s32-14.3 32-32l0-160c0-17.7-14.3-32-32-32L320 0zM80 32C35.8 32 0 67.8 0 112L0 432c0 44.2 35.8 80 80 80l320 0c44.2 0 80-35.8 80-80l0-112c0-17.7-14.3-32-32-32s-32 14.3-32 32l0 112c0 8.8-7.2 16-16 16L80 448c-8.8 0-16-7.2-16-16l0-320c0-8.8 7.2-16 16-16l112 0c17.7 0 32-14.3 32-32s-14.3-32-32-32L80 32z"/>
                        </svg>
                    </a>
                </div>
            </div>
        </div>
    </section>
    <section class="about-section"></section>
    <section class="portfolio-section">
        <div class="responsive-container">
            <div class="portfolio-heading-wrapper d-flex align-items-center justify-content-between">
                <h1 class="portfolio-heading">Portfolio</h1>
                <a href="#" class="portfolio-link">View Portfolio</a>
            </div>
            <div class="portfolio-images-wrapper">
                <div class="portfolio-images">
                    <img class="img-fluid" src="~/assets/images/portfolio-image-1.png" alt="portfolio-images">
                </div>
                <div class="portfolio-images">
                    <img class="img-fluid" src="~/assets/images/portfolio-image-2.png" alt="portfolio-images">
                </div>
                <div class="portfolio-images">
                    <img class="img-fluid" src="~/assets/images/portfolio-image-3.png" alt="portfolio-images">
                </div>
                <div class="portfolio-images">
                    <img class="img-fluid" src="~/assets/images/portfolio-image-4.png" alt="portfolio-images">
                </div>
                <div class="portfolio-images">
                    <img class="img-fluid" src="~/assets/images/portfolio-image-5.png" alt="portfolio-images">
                </div>
                <div class="portfolio-images">
                    <img class="img-fluid" src="~/assets/images/portfolio-image-6.png" alt="portfolio-images">
                </div>
                <div class="portfolio-images">
                    <img class="img-fluid" src="~/assets/images/portfolio-image-7.png" alt="portfolio-images">
                </div>
                <div class="portfolio-images">
                    <img class="img-fluid" src="~/assets/images/portfolio-image-8.png" alt="portfolio-images">
                </div>
            </div>
        </div>
    </section>

</template>


<style scoped>

</style>