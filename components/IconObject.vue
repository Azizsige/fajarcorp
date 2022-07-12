<template>
  <!-- <div
    class="rounded lg:h-64 lg:w-64 md:h-52 md:w-52 sm:h-32 sm:w-32 h-24 w-24"
  >
    <div class="h-3/4 grid place-content-center">
      <span
        class="lg:text-7xl md:text-3xl text-xl text-white"
        v-html="tag"
      ></span>
    </div>
    <div class="grid place-content-center">
      <span class="lg:text-4xl md:text-2xl text-lg text-white">{{
        label
      }}</span>
    </div>
  </div> -->
  <img class="mx-auto h-20 xl:h-72" :src="src" />
</template>

<style>
/* .icon-update {
  background-image: url("/assets/img/fajar web-1.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  box-shadow: inset 0 0 0 50vw rgba(243, 146, 33, 0.5);
}
.icon-product {
  background-image: url("/assets/img/fajar web-1.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  box-shadow: inset 0 0 0 50vw rgba(110, 171, 69, 0.5);
}
.icon-contact {
  background-image: url("/assets/img/fajar web-1.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  box-shadow: inset 0 0 0 50vw rgba(51, 132, 170, 0.5);
} */
</style>

<script>
export default {
  name: "IconObject",
  props: ["tag", "label", "src"],
};
</script>
