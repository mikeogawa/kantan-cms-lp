<script setup>
import { ref } from "vue";
</script>

<template>
    <!-- Newsletter Section Start -->
    <div id="subscribe" class="bg-theme-primary mt-10">
        <div class="container w-full lg:w-2/5 mx-auto px-5">
            <section class="py-16">
                <h2 class="text-3xl md:text-4xl font-medium text-center text-white mt-9 mb-10 font-theme-heading">Ready to revolutionize your content management experience</h2>
                <p class="text-white text-center my-7 font-theme-content text-lg"> 
                    Join us in our adventure by signing up for Kantan CMS today. Say hello to simplicity, efficiency, and productivity. Say hello to Kantan CMS.

                </p>

                <!-- <form @submit.prevent="handleSubmit()">
                    <div class="relative flex flex-col items-center lg:flex-row justify-center lg:space-x-3">
                        <div class="relative w-full lg:mb-0 font-theme-content">
                            <input v-model="email" @input="emailError = false" class="w-full py-3 px-5 text-sm text-gray-600 border-0 shadow-md rounded focus:ring-4 focus:ring-blue-300" type="text" name="newsletter_email" placeholder="Enter your email address" />
                            <div v-show="emailError">
                                <img class="absolute right-3 top-3" src="/images/icon-error.svg" alt="Error Icon" />
                                <div class="absolute w-full text-xs italic px-2 py-1 bg-theme-secondary text-white rounded">Whosps, make sure it's an email</div>
                            </div>
                        </div>

                        <Button type="submit" btn-type="secondary">Subscribe</Button>
                    </div>
                </form> -->
            </section>
        </div>
    </div>
    <!-- Newsletter Section End -->
</template>
