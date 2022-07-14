<template>
  <img class="clip_industri" :src="src" />
</template>

<style>
img.clip_industri {
  -webkit-clip-path: polygon(0% 0%, 88% 0%, 100% 100%, 0% 100%);
  clip-path: polygon(0% 0%, 88% 0%, 100% 100%, 0% 100%);
  border-radius: 15px;
}
</style>

<script>
export default {
  name: "ClipIndustri",
  props: ["src"],
};
</script>
