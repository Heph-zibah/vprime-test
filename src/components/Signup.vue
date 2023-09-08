<script setup>
import Logo from './Logo.vue';

</script>

<template>
    <section>
        <div class="md:flex min-h-screen ">
            <div class="md:w-8/12 text-white bg-black  pt-20">
                <div class="  max-w-xl mx-auto">
                    <h1 class="text-4xl font-bold">Create account</h1>
                    <form action="">
                        <div class="">
                            <label for="" class="block mt-7 mb-2">Email Address <span class="text-[#ff0000]">*</span></label>
                            <input type="email" class="w-full border border-[#292B36] py-4 rounded-md bg-transparent px-5" placeholder="you@example.com">
                        </div>
                        <div class="">
                            <label for="" class="block mt-7 mb-2">First name <span class="text-[#ff0000]">*</span></label>
                            <input type="text" class="w-full border border-[#292B36] py-4 rounded-md bg-transparent">
                        </div>
                        <div>
                            <label for="" class="block mt-7 mb-2">Password <span  class="text-[#ff0000]">*</span></label>
                            <input type="password" class="w-full border border-[#292B36] py-4 rounded-md bg-transparent">
                        </div>
                        <p class="mt-7 text-[#71717A]">By clicking "Start 20-day trial", you declare that you have read, understood and accepted our <a href="#" class="decoration-solid underline decoration-[#71717A]">privacy policy</a>.</p>
                        <div class="mt-7 ">
                            <button class="bg-[#87CEEB] py-2 px-4 rounded-md w-full">Login</button>
                           
                        </div>
                    </form>
                    <p class="text-[#71717A] mt-7">Already have an account? <a href="#" class="decoration-solid underline decoration-[#71717A]">Login</a></p>
                </div>
                <div class="px-10 flex items-center justify-between text-[#71717A] mt-24 mb-10">
                    <p>©2023 VPrime</p>
                    <ul class="flex space-x-3">
                        <li><a href="#">Need help?</a></li>
                        <li><a href="#">Legal notice</a></li>
                        <li><a href="#">Privacy policy</a></li>
                    </ul>
                </div>
            </div>
            <Logo/>


        </div>
    </section>
</template>

<style scoped>

</style>
