<script setup>
import features from "../data/features";
</script>

<template>
    <!-- Download Section Start -->
    <div id="download-section" class="container mx-auto px-5 md:w-4/5">
        <section class="py-16 pt-18">
            <div class="w-4/5 md:w-4/5 mx-auto py-20">
                <h2 class="text-3xl md:text-4xl font-semibold font-theme-heading text-center">Enter KANTAN CMS</h2>
                <p class="text-theme-grayish-blue text-center mt-7 font-theme-content text-lg">
                    Built on serverless technology, Kantan CMS eliminates the need for expensive servers and the headaches of traditional CMS platforms. Our user-friendly interface makes content management a breeze, empowering both designers and content editors to work more productively.
                </p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 mt-12">
                <div v-for="(feature) in features" :key="feature.id" class="shadow-lg rounded-lg">
                    <!-- <div class="flex justify-center mt-12">
                        <img :src="download.icon" alt="Browser Logo" />
                    </div> -->
                    <h3 class="text-2xl font-theme-heading font-medium text-center mt-6">{{ feature.title }}</h3>
                    <div class="my-2">
                        <img class="w-full" src="/images/bg-dots.svg" alt="Dot Backaground" />
                    </div>
                    <p class="text-md font-theme-content text-theme-grayish-blue text-center px-3 py-7">{{ feature.description }}</p>

                    <!-- <div class="flex justify-center mb-8">
                        <LinkButton btn-type="primary" :link="download.link" class="text-sm">Add & Install Extension</LinkButton>
                    </div> -->
                </div>
            </div>
        </section>
    </div>
    <!-- Download Section End -->
</template>
