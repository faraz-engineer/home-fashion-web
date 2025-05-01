<script setup>
import { ref, onMounted } from 'vue'

const filter = ref('all')
const gallery = ref(null)

const categories = ['all', 'fashion', 'beauty', 'makeup', 'model']

const capitalize = (str) => str.charAt(0).toUpperCase() + str.slice(1)

const applyFilter = (selected) => {
    filter.value = selected
    const items = gallery.value.querySelectorAll('.portfolio-images')

    items.forEach((item) => {
        const category = item.getAttribute('data-category')
        if (filter.value === 'all' || filter.value === category) {
            item.style.display = 'block'
        } else {
            item.style.display = 'none'
        }
    })
}


onMounted(() => {
    applyFilter('all')
})
</script>
<template>
    <section class="portfolio-section">
        <div class="responsive-container">
            <div class="professional-photographer-wrapper portfolio-wrapper">
                <div class="portfolio-content-wrapper d-flex align-items-center justify-content-between">
                    <div class="fashion-industry-heading p-0">
                        <h1 class="professional-photographer-heading p-0 m-0">Portfolio</h1>
                    </div>
                    <div class="portfolio-paragraph">
                        <p class="m-0 common-paragraph about-paragraph">Lorem ipsum dolor sit amet, consectetur
                            adipiscing elit, sed do eiusmod tempor
                            incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud
                            exercitation ullamco laboris
                        </p>
                    </div>
                </div>
                <div class="about-portfolio-image p-0">
                    <img class="img-fluid" src="~/assets/images/about-portfolio.jpg" alt="about-portfolio">
                </div>
            </div>
        </div>
    </section>
    <section class="portfolio">
        <div class="responsive-container">
            <div class="portfolio-page-wrapper">
                <div class="filter-links">
                    <a v-for="cat in categories" :key="cat" href="#" @click.prevent="applyFilter(cat)"
                        :class="{ active: filter === cat }">
                        {{ capitalize(cat) }}
                    </a>
                </div>
                <div class="portfolio-images-wrapper" ref="gallery">
                    <div class="portfolio-images" data-category="fashion">
                        <img class="img-fluid" src="~/assets/images/portfolio-image-1.png" alt="Fashion 1" />
                    </div>

                    <div class="portfolio-images" data-category="beauty">
                        <img class="img-fluid" src="~/assets/images/portfolio-image-2.png" alt="Fashion 2" />
                    </div>

                    <div class="portfolio-images" data-category="makeup">
                        <img class="img-fluid" src="~/assets/images/portfolio-image-3.png" alt="Beauty 1" />
                    </div>

                    <div class="portfolio-images" data-category="model">
                        <img class="img-fluid" src="~/assets/images/portfolio-image-4.png" alt="Beauty 2" />
                    </div>

                    <div class="portfolio-images" data-category="fashion">
                        <img class="img-fluid" src="~/assets/images/portfolio-image-5.png" alt="Fashion 3" />
                    </div>
                    <div class="portfolio-images" data-category="beauty">
                        <img class="img-fluid" src="~/assets/images/portfolio-page-image-1.png" alt="Fashion 3" />
                    </div>
                    <div class="portfolio-images" data-category="makeup">
                        <img class="img-fluid" src="~/assets/images/portfolio-page-image-2.png" alt="Fashion 3" />
                    </div>
                    <div class="portfolio-images" data-category="model">
                        <img class="img-fluid" src="~/assets/images/portfolio-page-image-3.png" alt="Fashion 3" />
                    </div>
                    <div class="portfolio-images" data-category="fashion">
                        <img class="img-fluid" src="~/assets/images/portfolio-page-image-4.png" alt="Fashion 3" />
                    </div>
                    <div class="portfolio-images" data-category="beauty">
                        <img class="img-fluid" src="~/assets/images/portfolio-page-image-5.png" alt="Fashion 3" />
                    </div>
                    <div class="portfolio-images" data-category="makeup">
                        <img class="img-fluid" src="~/assets/images/portfolio-page-image-14.png" alt="Fashion 3" />
                    </div>
                    <div class="portfolio-images" data-category="model">
                        <img class="img-fluid" src="~/assets/images/portfolio-image-7.png" alt="Fashion 3" />
                    </div>
                    <div class="portfolio-images" data-category="fashion">
                        <img class="img-fluid" src="~/assets/images/portfolio-image-6.png" alt="Fashion 3" />
                    </div>
                    <div class="portfolio-images" data-category="beauty">
                        <img class="img-fluid" src="~/assets/images/portfolio-image-8.png" alt="Fashion 3" />
                    </div>
                    <div class="portfolio-images" data-category="makeup">
                        <img class="img-fluid" src="~/assets/images/portfolio-image-1.png" alt="Fashion 3" />
                    </div>
                    <div class="portfolio-images" data-category="model">
                        <img class="img-fluid" src="~/assets/images/portfolio-image-2.png" alt="Fashion 3" />
                    </div>
                </div>
            </div>
        </div>
    </section>


    <lets-work-together />
</template>
<style scoped>
.filter-links {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 35px;
}

.filter-links a {
    text-decoration: none;
    transition: all 0.3s ease;
    font-size: 15px;
    font-weight: 600;
    text-transform: uppercase;
    color: #ffffffb3;

}

.filter-links a:hover {
    color: #efefef;
}

.filter-links a.active {
    background: #000;
    color: #fff;
}
</style>