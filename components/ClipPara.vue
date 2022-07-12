<template>
    <img class="clip_para" :src="src">
</template>

<style>
    img.clip_para {
        -webkit-clip-path: polygon(25% 0%, 100% 0%, 75% 100%, 0% 100%);
        clip-path: polygon(25% 0%, 100% 0%, 75% 100%, 0% 100%);
    }
</style>

<script>
export default {
    name: 'ClipPara',
    props: ['src']
}
</script>