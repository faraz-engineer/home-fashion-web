<script setup>
import { ref } from 'vue';
const isOpen1 = ref(false);
const isOpen2 = ref(false);
const isOpen3 = ref(false);
const isOpen4 = ref(false);
const isOpen5 = ref(false);
const isOpen6 = ref(false);



</script>

<template>
    <section class="contact-section">
        <div class="responsive-container">
            <div class="contact-wrapper">
                <div class="contact-content d-flex flex-column gap-4">
                    <h1 class="contact-heading">Let's Discuss your project!</h1>
                    <p class="common-paragraph about-paragraph">Lorem ipsum dolor sit amet, consectetur adipiscing elit,
                        sed do eiusmod tempor
                        incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
                    </p>
                    <div class="contact-icon d-flex align-items-center gap-3">
                        <img class="mail-icon" src="~/assets/images/mail.svg" alt="mail">
                        <p class="common-paragraph about-paragraph text-white">Email@demo.com</p>
                    </div>
                    <div class="contact-icon d-flex align-items-center gap-3">
                        <img class="mail-icon" src="~/assets/images/telephone.svg" alt="mail">
                        <p class="common-paragraph about-paragraph text-white">202-555-0148</p>
                    </div>
                    <div class="d-flex gap-4 align-items-center">
                        <div class="social-link">
                            <a href="#" class="social-icons-link">
                                <svg class="social-icons" width="64px" height="64px" viewBox="0 -3 20 20" version="1.1"
                                    xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                                    fill="#000000">
                                    <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                                    <g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g>
                                    <g id="SVGRepo_iconCarrier">
                                        <title>youtube [#168]</title>
                                        <desc>Created with Sketch.</desc>
                                        <defs></defs>
                                        <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                                            <g id="Dribbble-Light-Preview"
                                                transform="translate(-300.000000, -7442.000000)" fill="#000000">
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
                </div>
                <div class="contact-form-wrapper">
                    <form>
                        <input type="text" id="name" placeholder="Name" required>

                        <input type="email" id="email" placeholder="Email Address" required>

                        <textarea id="message" placeholder="Message" rows="4" required></textarea>

                        <a href="#" class="portfolio-link">SUBMIT</a>
                    </form>
                </div>
            </div>
        </div>
    </section>
    <section class="faq-question-section">
        <div class="responsive-container">
            <div class="faq-heading">
                <h1>Frequently Asked Questions</h1>
            </div>
            <div class="faq-wrapper d-flex align-items-center justify-content-between">
                <div class="faq-content-wrapper d-flex flex-column gap-4">
                    <div class="faq-content" @click="isOpen1 = !isOpen1">
                        <div class="faq-question">
                            <p class="common-paragraph about-paragraph text-white">1. Impedit egestas aliquet?</p>
                            <span class="faq-question-link">
                                <img v-if="!isOpen1" class="faq-image" src="~/assets/images/plus.svg" alt="faq-image">
                                <img v-else class="faq-image minus-icon" src="~/assets/images/minus.svg"
                                    alt="faq-image">
                            </span>
                        </div>
                        <Transition name="faq-slide">
                            <p v-if="isOpen1" class="common-paragraph about-paragraph text-white faq-paragraph">
                                Lorem ipsum dolor sit
                                amet,
                                consectetur adipiscing
                                elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.
                            </p>
                        </Transition>
                    </div>
                    <div class="faq-content" @click="isOpen2 = !isOpen2">
                        <div class="faq-question">
                            <p class="common-paragraph about-paragraph text-white">2.Sapien class quo temporibus?</p>
                            <span class="faq-question-link">
                                <img v-if="!isOpen2" class="faq-image" src="~/assets/images/plus.svg" alt="faq-image">
                                <img v-else class="faq-image minus-icon" src="~/assets/images/minus.svg"
                                    alt="faq-image">
                            </span>
                        </div>
                        <Transition name="faq-slide">
                            <p v-if="isOpen2" class="common-paragraph about-paragraph text-white faq-paragraph">Lorem
                                ipsum
                                dolor sit amet,
                                consectetur adipiscing
                                elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.
                            </p>
                        </Transition>
                    </div>
                    <div class="faq-content" @click="isOpen3 = !isOpen3">
                        <div class="faq-question">
                            <p class="common-paragraph about-paragraph text-white">3.Elementum voluptate sodales?</p>
                            <span class="faq-question-link">
                                <img v-if="!isOpen3" class="faq-image" src="~/assets/images/plus.svg" alt="faq-image">
                                <img v-else class="faq-image minus-icon" src="~/assets/images/minus.svg"
                                    alt="faq-image">
                            </span>
                        </div>
                        <Transition name="faq-slide">
                            <p v-if="isOpen3" class="common-paragraph about-paragraph text-white faq-paragraph">Lorem
                                ipsum
                                dolor sit amet,
                                consectetur adipiscing
                                elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.
                            </p>
                        </Transition>
                    </div>
                </div>
                <div class="faq-content-wrapper d-flex flex-column gap-4">
                    <div class="faq-content" @click="isOpen4 = !isOpen4">
                        <div class="faq-question">
                            <p class="common-paragraph about-paragraph text-white">4. Lorem ipsum dolor sit amet consectetur adipiscing?</p>
                            <span class="faq-question-link">
                                <img v-if="!isOpen4" class="faq-image" src="~/assets/images/plus.svg" alt="faq-image">
                                <img v-else class="faq-image minus-icon" src="~/assets/images/minus.svg"
                                    alt="faq-image">
                            </span>
                        </div>
                        <Transition name="faq-slide">
                            <p v-if="isOpen4" class="common-paragraph about-paragraph text-white faq-paragraph">Lorem
                                ipsum
                                dolor sit amet,
                                consectetur adipiscing
                                elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.
                            </p>
                        </Transition>
                    </div>
                    <div class="faq-content" @click="isOpen5 = !isOpen5">
                        <div class="faq-question">
                            <p class="common-paragraph about-paragraph text-white">5. Sed do eiusmod tempor incididunt ut labore?</p>
                            <span class="faq-question-link">
                                <img v-if="!isOpen5" class="faq-image" src="~/assets/images/plus.svg" alt="faq-image">
                                <img v-else class="faq-image minus-icon" src="~/assets/images/minus.svg"
                                    alt="faq-image">
                            </span>
                        </div>
                        <Transition name="faq-slide">
                            <p v-if="isOpen5" class="common-paragraph about-paragraph text-white faq-paragraph">Lorem
                                ipsum
                                dolor sit amet,
                                consectetur adipiscing
                                elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.
                            </p>
                        </Transition>
                    </div>
                    <div class="faq-content" @click="isOpen6 = !isOpen6">
                        <div class="faq-question">
                            <p class="common-paragraph about-paragraph text-white">6. Duis aute irure dolor in reprehenderit in voluptate?</p>
                            <span class="faq-question-link">
                                <img v-if="!isOpen6" class="faq-image" src="~/assets/images/plus.svg" alt="faq-image">
                                <img v-else class="faq-image minus-icon" src="~/assets/images/minus.svg"
                                    alt="faq-image">
                            </span>
                        </div>
                        <Transition name="faq-slide">
                            <p v-if="isOpen6" class="common-paragraph about-paragraph text-white faq-paragraph">Lorem
                                ipsum
                                dolor sit amet,
                                consectetur adipiscing
                                elit. Ut elit tellus, luctus nec ullamcorper mattis, pulvinar dapibus leo.
                            </p>
                        </Transition>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<style scoped>
.faq-slide-enter-active,
.faq-slide-leave-active {
    transition: all 0.3s ease;
    overflow: hidden;
}

.faq-slide-enter-from,
.faq-slide-leave-to {
    max-height: 0;
    opacity: 0;
    padding-top: 0;
    padding-bottom: 0;
}

.faq-slide-enter-to,
.faq-slide-leave-from {
    opacity: 1;
    padding-top: 1rem;
    padding-bottom: 1rem;
}
</style>
