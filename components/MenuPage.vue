<template>
    <div>
        <div class="bg-gray-100">
            <div class="flex justify-center items-center mx-auto py-32 ">
                <h2 class="lg:text-5xl md:text-3xl textl-xl">{{ pageTitle }}</h2>
            </div>
        </div>
        <div class="bg-white">
            <div class="container mx-auto py-16"/>
        </div>
    </div>
</template>

<style>
    img.clip_para {
        -webkit-clip-path: polygon(25% 0%, 100% 0%, 75% 100%, 0% 100%);
        clip-path: polygon(25% 0%, 100% 0%, 75% 100%, 0% 100%);
    }
</style>

<script>
export default {
    name: 'MenuPage',
    props: ['pageTitle']
}
</script>