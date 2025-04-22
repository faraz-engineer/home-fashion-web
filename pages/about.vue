<script setup>
import {ref, onMounted} from "vue";

onMounted(() => {

})


</script>
<template>
    <section class="professional-photographer">
        <div class="responsive-container">
            <div class="professional-photographer-wrapper">
                <div class="fashion-industry-heading p-0">
                    <h1 class="professional-photographer-heading">
                        professional photographer for top-tier brands
                    </h1>
                </div>
                <div class="photographer-about-wrapper d-flex align-items-center">
                    <div class="photographer-image">
                        <img class="img-fluid" src="~/assets/images/photographer.jpg" alt="photographer-image">
                    </div>
                    <div class="photographer-content">
                        <div class="photo-shoot-content d-flex flex-column">
                            <h1 class="portfolio-heading">
                                I'm Mason Leblanc
                            </h1>
                            <p class="common-paragraph about-paragraph">Lorem ipsum dolor sit amet, consectetur
                                adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                                enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
                                commodo consequat.
                            </p>
                            <a class="portfolio-link about-link" href="#">Download Cv</a>
                        </div>
                    </div>
                </div>
                <div class="awards-list-wrapper d-flex">
                    <div class="awards-list">
                        <h1 class="common-heading mb-5">Awards</h1>
                        <div class="awards-content pb-3">
                            <p class="common-paragraph">International Photography Award</p>
                            <p class="reviews-title">2016</p>
                        </div>
                        <div class="awards-content pb-3">
                            <p class="common-paragraph">Fashion Photography Award</p>
                            <p class="reviews-title">2019</p>
                        </div>
                        <div class="awards-content pb-3">
                            <p class="common-paragraph">Best Shot Award</p>
                            <p class="reviews-title">2022</p>
                        </div>
                        <div class="awards-content pb-3">
                            <p class="common-paragraph">Euro Lens Award</p>
                            <p class="reviews-title">2022</p>
                        </div>
                    </div>
                    <div class="featured-in-content">
                        <h1 class="common-heading mb-5">Featured In</h1>
                        <div class="awards-content pb-3">
                            <p class="common-paragraph">Vogue Magazine</p>
                            <p class="reviews-title">2018</p>
                        </div>
                        <div class="awards-content pb-3">
                            <p class="common-paragraph">Aperture Magazine</p>
                            <p class="reviews-title">2020</p>
                        </div>
                        <div class="awards-content pb-3">
                            <p class="common-paragraph">PetaPixel Website</p>
                            <p class="reviews-title">2022</p>
                        </div>
                    </div>
                    <div class="education-content">
                        <h1 class="common-heading mb-5">Education</h1>
                        <div class="awards-content pb-3">
                            <p class="common-paragraph">Certified Professional Photographer</p>
                            <p class="reviews-title">New York Institute of Photography, New York</p>
                        </div>
                        <div class="awards-content pb-3">
                            <p class="common-paragraph">Masters of Fine Arts</p>
                            <p class="reviews-title">University of Washington, Seattle</p>
                        </div>
                        <div class="awards-content pb-3">
                            <p class="common-paragraph">Bachelor of Arts</p>
                            <p class="reviews-title">University of Washington, Seattle</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="about-portfolio-image">
                <img class="img-fluid" src="~/assets/images/about-portfolio.jpg" alt="about-portfolio">
            </div>
        </div>
    </section>
    <section class="work-experience">
        <div class="responsive-container">
            <div class="work-experience-wrapper d-flex">
                <div class="photo-shoot-content d-flex flex-column">
                    <h1 class="portfolio-heading">Work Experience</h1>
                    <p class="common-paragraph about-paragraph">At vero eos et accusamus et iusto odio dignissimos
                        ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas
                        molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia
                        deserunt mollitia animi.
                    </p>
                </div>
                <div class="magazine-wrapper">
                    <div class="magazine-content mb-5">
                        <h1 class="magazine-heading">Fashion Week Magazine</h1>
                        <div class="d-flex justify-content-between align-items-center">
                            <p class="reviews-title">Director of Photography</p>
                            <p class="reviews-title">2017 – Present</p>
                        </div>
                        <div class="border-line"></div>
                        <p class="common-paragraph about-paragraph pb-3">Lorem ipsum dolor sit amet, consectetur
                            adipiscing
                            elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
                            veniam.
                        </p>
                    </div>
                    <div class="magazine-content mb-5">
                        <h1 class="magazine-heading">Abstract Modeling Agency</h1>
                        <div class="d-flex justify-content-between align-items-center">
                            <p class="reviews-title">Senior Photographer</p>
                            <p class="reviews-title">2015 – 2017</p>
                        </div>
                        <div class="border-line"></div>
                        <p class="common-paragraph about-paragraph pb-3">Duis aute irure dolor in reprehenderit in
                            voluptate velit esse cillum dolore eu fugiat nulla pariatur excepteur sint occaecat
                            cupidatat non proident,
                        </p>
                    </div>
                    <div class="magazine-content mb-5">
                        <h1 class="magazine-heading">Freelance Photographer</h1>
                        <div class="d-flex justify-content-between align-items-center">
                            <p class="reviews-title">Self-employed</p>
                            <p class="reviews-title">2011 – Present</p>
                        </div>
                        <div class="border-line"></div>
                        <p class="common-paragraph about-paragraph pb-3">Sed ut perspiciatis unde omnis iste natus error
                            sit voluptatem accusantium doloremque laudantium, totam rem aperiam
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <lets-work-together/>


</template>
<style scoped>

</style>