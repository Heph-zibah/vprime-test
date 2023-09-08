<script setup>
import Logo from './Logo.vue';

</script>

<template>
    <section>
        <div class="md:flex min-h-screen ">
            <div class="md:w-8/12 text-white bg-black  pt-20">
                <div class="  max-w-xl mx-auto">
                    <h1 class="text-4xl font-bold">Log in to your account</h1>
                    <form action="">
                        <div class="">
                            <label for="" class="block mt-7 mb-2">Email Address <span class="text-[#ff0000]">*</span></label>
                            <input type="email" class="w-full border border-[#292B36] py-4 rounded-md bg-transparent">
                        </div>
                        <div>
                            <label for="" class="block mt-7 mb-2">Password <span  class="text-[#ff0000]">*</span></label>
                            <input type="password" class="w-full border border-[#292B36] py-4 rounded-md bg-transparent">
                        </div>
                        <div class="mt-7 flex justify-between items-center">
                            <button class="bg-[#87CEEB] py-2 px-4 rounded-md">Login</button>
                            <a href="#" class="hover:text-[#87CEEB] text-[#71717A] ">Forgot Password?</a>
                        </div>
                    </form>
                    <p class="text-[#71717A] mt-7">Don't have an account yet? <a href="#" class="decoration-solid underline decoration-[#71717A]">Sign up</a></p>
                </div>
                <div class="px-10 flex items-center justify-between text-[#71717A] mt-28">
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
