<template>
  <div :id="id" class="icon h-[75vh] mb-5 flex justify-center items-center">
    <font-awesome-icon
      icon="fa-solid fa-circle-play"
      class="text-white text-6xl xl:text-8xl"
    />
  </div>
</template>

<style>
#kehutanan {
  background-image: url("/assets/img/hero-bg.webp");
  background-size: cover;
  object-fit: cover;
  object-position: center;
}
#pertanian {
  background-image: url("/assets/img/hero-pertanian.png");
  background-size: cover;
  object-fit: cover;
  object-position: center;
}
#angkutan {
  background-image: url("/assets/img/hero-angkutan.png");
  background-size: cover;
  object-fit: cover;
  object-position: center;
}
</style>

<script>
export default {
  name: "HeroIndustri",
  props: ["src, id"],
};
</script>
