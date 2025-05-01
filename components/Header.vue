<script setup>
import {ref} from 'vue'


</script>

<template>
    <header>
        <div class="header-wrapper">
            <div class="header-top-bar">
                <div class="responsive-container">
                    <div class="logo-image-link">
                        <a href="/">
                            <img class="logo-image" src="~/assets/images/mason-leblanc.svg" alt="logo-image">
                        </a>
                    </div>
                </div>

            </div>
            <div class="bottom-header">
                <div class="responsive-container">
                    <div class="header-links">
                        <ul class="navbar-user-links">
                            <li>
                                <a class="navbar-links" href="/">Home</a>
                                <a class="navbar-links" href="/about">About</a>
                                <a class="navbar-links" href="/portfolio">Portfolio</a>
                                <a class="navbar-links" href="/services">Services</a>
                                <a class="navbar-links" href="/contact">Contact</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

    </header>

</template>

<style scoped></style>
