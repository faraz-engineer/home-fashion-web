<script setup>
import {ref, onMounted} from 'vue'
import LetsWorkTogether from "~/components/lets-work-together.vue";

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
    <section class="about-section">
        <div class="background-image"></div>
        <div class="gradient-overlay"></div>
        <div class="responsive-container">
            <div class="d-flex about-wrapper  justify-content-between">
                <div class="social-icons-link-wrapper">
                    <div class="social-link">
                        <a href="#" class="social-icons-link">
                            <svg class="social-icons" width="64px" height="64px" viewBox="0 -3 20 20" version="1.1"
                                 xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                 fill="#000000">
                                <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                                <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                                <g id="SVGRepo_iconCarrier"><title>youtube [#168]</title>
                                    <desc>Created with Sketch.</desc>
                                    <defs></defs>
                                    <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                        <g id="Dribbble-Light-Preview"
                                           transform="translate(-300.000000, -7442.000000)"
                                           fill="#000000">
                                            <g id="icons" transform="translate(56.000000, 160.000000)">
                                                <path
                                                    d="M251.988432,7291.58588 L251.988432,7285.97425 C253.980638,7286.91168 255.523602,7287.8172 257.348463,7288.79353 C255.843351,7289.62824 253.980638,7290.56468 251.988432,7291.58588 M263.090998,7283.18289 C262.747343,7282.73013 262.161634,7282.37809 261.538073,7282.26141 C259.705243,7281.91336 248.270974,7281.91237 246.439141,7282.26141 C245.939097,7282.35515 245.493839,7282.58153 245.111335,7282.93357 C243.49964,7284.42947 244.004664,7292.45151 244.393145,7293.75096 C244.556505,7294.31342 244.767679,7294.71931 245.033639,7294.98558 C245.376298,7295.33761 245.845463,7295.57995 246.384355,7295.68865 C247.893451,7296.0008 255.668037,7296.17532 261.506198,7295.73552 C262.044094,7295.64178 262.520231,7295.39147 262.895762,7295.02447 C264.385932,7293.53455 264.28433,7285.06174 263.090998,7283.18289"
                                                    id="youtube-[#168]">

                                                </path>
                                            </g>
                                        </g>
                                    </g>
                                </g>
                            </svg>
                        </a>
                    </div>
                    <div class="social-link">
                        <a href="#" class="social-icons-link">
                            <svg class="social-icons" viewBox="0 0 24 24" fill="none"
                                 xmlns="http://www.w3.org/2000/svg">
                                <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                                <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                                <g id="SVGRepo_iconCarrier">
                                    <path
                                        d="M18.72 3.99997H5.37C5.19793 3.99191 5.02595 4.01786 4.86392 4.07635C4.70189 4.13484 4.55299 4.22471 4.42573 4.34081C4.29848 4.45692 4.19537 4.59699 4.12232 4.75299C4.04927 4.909 4.0077 5.07788 4 5.24997V18.63C4.01008 18.9901 4.15766 19.3328 4.41243 19.5875C4.6672 19.8423 5.00984 19.9899 5.37 20H18.72C19.0701 19.9844 19.4002 19.8322 19.6395 19.5761C19.8788 19.32 20.0082 18.9804 20 18.63V5.24997C20.0029 5.08247 19.9715 4.91616 19.9078 4.76122C19.8441 4.60629 19.7494 4.466 19.6295 4.34895C19.5097 4.23191 19.3672 4.14059 19.2108 4.08058C19.0544 4.02057 18.8874 3.99314 18.72 3.99997ZM9 17.34H6.67V10.21H9V17.34ZM7.89 9.12997C7.72741 9.13564 7.5654 9.10762 7.41416 9.04768C7.26291 8.98774 7.12569 8.89717 7.01113 8.78166C6.89656 8.66615 6.80711 8.5282 6.74841 8.37647C6.6897 8.22474 6.66301 8.06251 6.67 7.89997C6.66281 7.73567 6.69004 7.57169 6.74995 7.41854C6.80986 7.26538 6.90112 7.12644 7.01787 7.01063C7.13463 6.89481 7.2743 6.80468 7.42793 6.74602C7.58157 6.68735 7.74577 6.66145 7.91 6.66997C8.07259 6.66431 8.2346 6.69232 8.38584 6.75226C8.53709 6.8122 8.67431 6.90277 8.78887 7.01828C8.90344 7.13379 8.99289 7.27174 9.05159 7.42347C9.1103 7.5752 9.13699 7.73743 9.13 7.89997C9.13719 8.06427 9.10996 8.22825 9.05005 8.3814C8.99014 8.53456 8.89888 8.6735 8.78213 8.78931C8.66537 8.90513 8.5257 8.99526 8.37207 9.05392C8.21843 9.11259 8.05423 9.13849 7.89 9.12997ZM17.34 17.34H15V13.44C15 12.51 14.67 11.87 13.84 11.87C13.5822 11.8722 13.3313 11.9541 13.1219 12.1045C12.9124 12.2549 12.7546 12.4664 12.67 12.71C12.605 12.8926 12.5778 13.0865 12.59 13.28V17.34H10.29V10.21H12.59V11.21C12.7945 10.8343 13.0988 10.5225 13.4694 10.3089C13.84 10.0954 14.2624 9.98848 14.69 9.99997C16.2 9.99997 17.34 11 17.34 13.13V17.34Z"
                                        fill="#000000">
                                    </path>
                                </g>
                            </svg>
                        </a>
                    </div>
                    <div class="social-link">
                        <a href="#" class="social-icons-link">
                            <svg class="social-icons" viewBox="0 0 24 24" fill="none"
                                 xmlns="http://www.w3.org/2000/svg">
                                <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                                <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                                <g id="SVGRepo_iconCarrier">
                                    <path fill-rule="evenodd" clip-rule="evenodd"
                                          d="M12 18C15.3137 18 18 15.3137 18 12C18 8.68629 15.3137 6 12 6C8.68629 6 6 8.68629 6 12C6 15.3137 8.68629 18 12 18ZM12 16C14.2091 16 16 14.2091 16 12C16 9.79086 14.2091 8 12 8C9.79086 8 8 9.79086 8 12C8 14.2091 9.79086 16 12 16Z"
                                          fill="#0F0F0F">
                                    </path>
                                    <path
                                        d="M18 5C17.4477 5 17 5.44772 17 6C17 6.55228 17.4477 7 18 7C18.5523 7 19 6.55228 19 6C19 5.44772 18.5523 5 18 5Z"
                                        fill="#0F0F0F">
                                    </path>
                                    <path fill-rule="evenodd" clip-rule="evenodd"
                                          d="M1.65396 4.27606C1 5.55953 1 7.23969 1 10.6V13.4C1 16.7603 1 18.4405 1.65396 19.7239C2.2292 20.8529 3.14708 21.7708 4.27606 22.346C5.55953 23 7.23969 23 10.6 23H13.4C16.7603 23 18.4405 23 19.7239 22.346C20.8529 21.7708 21.7708 20.8529 22.346 19.7239C23 18.4405 23 16.7603 23 13.4V10.6C23 7.23969 23 5.55953 22.346 4.27606C21.7708 3.14708 20.8529 2.2292 19.7239 1.65396C18.4405 1 16.7603 1 13.4 1H10.6C7.23969 1 5.55953 1 4.27606 1.65396C3.14708 2.2292 2.2292 3.14708 1.65396 4.27606ZM13.4 3H10.6C8.88684 3 7.72225 3.00156 6.82208 3.0751C5.94524 3.14674 5.49684 3.27659 5.18404 3.43597C4.43139 3.81947 3.81947 4.43139 3.43597 5.18404C3.27659 5.49684 3.14674 5.94524 3.0751 6.82208C3.00156 7.72225 3 8.88684 3 10.6V13.4C3 15.1132 3.00156 16.2777 3.0751 17.1779C3.14674 18.0548 3.27659 18.5032 3.43597 18.816C3.81947 19.5686 4.43139 20.1805 5.18404 20.564C5.49684 20.7234 5.94524 20.8533 6.82208 20.9249C7.72225 20.9984 8.88684 21 10.6 21H13.4C15.1132 21 16.2777 20.9984 17.1779 20.9249C18.0548 20.8533 18.5032 20.7234 18.816 20.564C19.5686 20.1805 20.1805 19.5686 20.564 18.816C20.7234 18.5032 20.8533 18.0548 20.9249 17.1779C20.9984 16.2777 21 15.1132 21 13.4V10.6C21 8.88684 20.9984 7.72225 20.9249 6.82208C20.8533 5.94524 20.7234 5.49684 20.564 5.18404C20.1805 4.43139 19.5686 3.81947 18.816 3.43597C18.5032 3.27659 18.0548 3.14674 17.1779 3.0751C16.2777 3.00156 15.1132 3 13.4 3Z"
                                          fill="#0F0F0F">
                                    </path>
                                </g>
                            </svg>

                        </a>
                    </div>
                    <div class="social-link">
                        <a href="#" class="social-icons-link">
                            <svg class="social-icons" fill="#000000" viewBox="0 0 24 24"
                                 xmlns="http://www.w3.org/2000/svg">
                                <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                                <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                                <g id="SVGRepo_iconCarrier">
                                    <path
                                        d="M12 2.03998C6.5 2.03998 2 6.52998 2 12.06C2 17.06 5.66 21.21 10.44 21.96V14.96H7.9V12.06H10.44V9.84998C10.44 7.33998 11.93 5.95998 14.22 5.95998C15.31 5.95998 16.45 6.14998 16.45 6.14998V8.61998H15.19C13.95 8.61998 13.56 9.38998 13.56 10.18V12.06H16.34L15.89 14.96H13.56V21.96C15.9164 21.5878 18.0622 20.3855 19.6099 18.57C21.1576 16.7546 22.0054 14.4456 22 12.06C22 6.52998 17.5 2.03998 12 2.03998Z">
                                    </path>
                                </g>
                            </svg>
                        </a>
                    </div>
                </div>
                <div class="about-description-wrapper d-flex align-items-start flex-column">
                    <p class="common-paragraph">
                        Lorem ipsum dolor sit amet consectetur adipiscing elit Ut et massa mi. Aliquam in hendrerit
                        urna. Pellentesque sit amet sapien fringilla, mattis ligula consectetur, ultrices mauris.
                        Maecenas vitae mattis tellus. Nullam quis imperdiet augue. Vestibulum auctor ornare leo, non
                        suscipit magna interdum eu. Curability
                    </p>
                    <p class="common-paragraph about-paragraph">
                        Erat placerat. In iaculis arcu eros, eget tempus orci facilisis id. Praesent lorem orci,
                        mattis
                        non efficitur id, ultricies vel nibh. Sed volutpat lacus vitae gravida viverra. Fusce vel
                        tempor
                        elit. Proin tempus, magna id scelerisque vestibulum, nulla ex
                    </p>
                    <p class="common-paragraph about-paragraph">
                        Pharetra sapien, tempor posuere massa neque nec felis. Aliquam sem ipsum, vehicula ac tortor
                        vel, egestas ullamcorper dui. Curabitur at risus sodales, tristique est id, euismod justo.
                        Mauris nec leo non libero sodales lobortis. Quisque a neque pretium, dictum tellus vitae,
                        euismod neque. Nulla facilisi. Phasellus ultricies dignissim nibh ut.
                    </p>
                    <p class="common-paragraph about-paragraph">
                        Nam et quam sit amet turpis finibus maximus tempor eget augue. Aenean at ultricies lorem.
                        Sed
                        egestas ligula tortor, sit amet mattis ex feugiat non. Duis purus diam, dictum et ante at,
                        commodo iaculis urna. Aenean lacinia, nisl id vehicula condimentum, enim massa.
                    </p>
                    <a href="#" class="portfolio-link">Read Full Bio</a>
                </div>
                <div class="social-icons-link-wrapper"></div>
            </div>
        </div>
    </section>
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
    <section class="services-section">
        <div class="responsive-container">
            <div class="services-heading">
                <h1 class="portfolio-heading text-center">Services</h1>
                <div class="services-wrapper d-flex align-items-center justify-content-between">
                    <div class="services-content d-flex align-items-center flex-column">
                        <div class="photo-shoot-content d-flex flex-column">
                            <h1 class="common-heading">Photoshoot</h1>
                            <p class="common-paragraph about-paragraph">Nam et quam sit amet turpis finibus maximus
                                tempor eget augue. Aenean at ultricies lorem. Sed egestas ligula tortor,
                            </p>
                            <a class="explore-link" href="#">Explore</a>
                        </div>
                        <div class="photo-shoot-content d-flex flex-column">
                            <h1 class="common-heading">Editing</h1>
                            <p class="common-paragraph about-paragraph">Duis aute irure dolor in reprehenderit in
                                voluptate velit esse cillum dolore eu fugiat nulla pariatur
                            </p>
                            <a class="explore-link" href="#">Explore</a>
                        </div>
                    </div>
                    <div class="service-image">
                        <img class="img-fluid" src="~/assets/images/services-image.jpg" alt="service-image">
                    </div>
                    <div class="services-content d-flex align-items-center flex-column">
                        <div class="photo-shoot-content d-flex flex-column">
                            <h1 class="common-heading">Retouching</h1>
                            <p class="common-paragraph about-paragraph">Lorem ipsum dolor sit amet, consectetur
                                adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
                            </p>
                            <a class="explore-link" href="#">Explore</a>
                        </div>
                        <div class="photo-shoot-content d-flex flex-column">
                            <h1 class="common-heading">Lightning</h1>
                            <p class="common-paragraph about-paragraph">Excepteur sint occaecat cupidatat non proident,
                                sunt in culpa qui officia deserunt mollit anim id est laborum.
                            </p>
                            <a class="explore-link" href="#">Explore</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section class="reviews-section">
        <div class="responsive-container">
            <div class="reviews-wrapper d-flex  justify-content-between">
                <div class="left-quotes-image">
                    <svg fill="#ffffff" version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg"
                        width="35px" height="35px"
                         viewBox="0 0 23.517 23.517" xml:space="preserve"><g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                        <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                        <g id="SVGRepo_iconCarrier">
                            <g>
                                <path
                                    d="M8.075,0.333c0.594,0,1.504,0.041,2.729,0.119v4.569c-3.722,0-5.578,1.722-5.578,5.164l0.06,2.077h3.856v10.92H0V11.373 C0.001,4.012,2.693,0.333,8.075,0.333z M23.517,5.022V0.453c-1.065-0.078-1.817-0.119-2.254-0.119 c-5.381,0-8.071,3.68-8.071,11.041v11.809h9.141v-10.92h-3.857l-0.059-2.077C18.412,6.942,20.115,5.221,23.517,5.022z">
                                </path>
                            </g>
                        </g>
                    </svg>
                </div>
                <div class="reviews-content d-flex flex-column">
                    <h4 class="reviews-heading">
                        Erat placerat. In iaculis arcu eros, eget tempus orci facilisis id. Praesent lorem orci, mattis
                        non efficitur id, ultricies vel nibh. Sed volutpat lacus vitae gravida viverra. Fusce vel tempor
                        elit. Proin tempus, magna id scelerisque vestibulum, nulla ex
                    </h4>
                    <div class="reviews-image d-flex align-items-center">
                        <img src="~/assets/images/face.png" alt="face">
                        <div class="reviews-image-content d-flex flex-column">
                            <p class="review-name">Jenny Raulph</p>
                            <p class="reviews-title">Owner at Girl Gang</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <lets-work-together />
</template>


<style scoped>

</style>