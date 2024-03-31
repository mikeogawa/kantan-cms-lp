<script setup>

import features from '../data/features.js';
import { ref } from 'vue';

let isOpen = ref(1);

</script>

<template>
    <!-- Features Section Start -->
    <div id="features" class="container mx-auto px-5 bg-purple-100">
        <section class="py-[10rem] relative">
            <div class="w-4/5 md:w-4/5 mx-auto">
                <h2 class="text-3xl md:text-4xl font-semibold font-theme-heading text-center">Why?</h2>
                <p class=" text-center mt-7 font-theme-content text-lg">
                    Are you tired of the hassle and expense of managing servers for your CMS? The burden falls on you to maintain costly servers, and as your CMS data grows, so do the expenses. Not to mention the headache of coordinating between designers and content editors, and the lack of collaboration features for teams.
                </p>
            </div>

        </section>
    </div>
    <!-- Features Section End -->
</template>
