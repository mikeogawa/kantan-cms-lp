<script setup>
    import { ref } from 'vue';

    let mobileNav = ref(false);

    let toggleMobileNav = () => {
        mobileNav.value = !mobileNav.value
    }
    import image from "/images/logo.png"
</script>

<template>
    <!-- Navbar Start -->
    <div class="container mx-auto px-5">
        <header class="flex justify-between py-12 items-center text-2xl">
            
            <div class="flex items-center">
                <img src="/images/logo.png" style="height:3rem"/> 
                <span>KANTAN-CMS</span>
            </div>
            

        </header>


        <!-- Mobile Menu End-->
    </div>
    <!-- Navbar End -->
</template>