<template>
  <card title="About" class="text-jusitfy">
    <div class="p-4 dark:text-white">
      <p class="font-semibold">Hello, welcome to my personnal Page!</p>
      <br />
      <p>
        My name is Alexandre Zenon. I am a Belgian computer science student.
      </p>
      <br />
      <p>
        During my free time I enjoy programming frontends and backends for
        various projects and ideas. I also like inline skating and inline
        hockey.
      </p>
      <br />
      <p>
        I lived for a year in Kawasaki, Japan. It was one of the best
        experiences I have had in my life.
      </p>
    </div>
  </card>
</template>

<script>
import Card from "~/components/Card/Card.vue";
export default {
  name: "CardAboutMe",
  components: {
    Card,
  },
};
</script>

<style>
</style>
