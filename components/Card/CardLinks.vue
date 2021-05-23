<template>
  <card title="My links">
    <div class="grid grid-cols-4 gap-4 pt-5 pb-6 px-4 dark:text-white">
      <a
        class="rounded-xl shadow-md"
        href="https://github.com/Ahzed11/"
        target="_blank"
      >
        <icon-github />
      </a>
      <a
        class="rounded-xl shadow-md"
        href="https://www.linkedin.com/in/alexandre-zenon/"
        target="_blank"
      >
        <icon-linkedin />
      </a>
      <a
        class="rounded-xl shadow-md"
        href="https://ahzed.itch.io/"
        target="_blank"
      >
        <icon-itchio />
      </a>
      <a
        class="rounded-xl shadow-md"
        href="https://www.youtube.com/channel/UCm0Tstopf2nxISi6bQ-WAiw"
        target="_blank"
      >
        <icon-youtube />
      </a>
      <!--
      <a class="rounded-xl shadow-md" target="_blank">
        <icon-instagram />
      </a>-->
    </div>
  </card>
</template>

<script>
import Card from "~/components/Card/Card.vue";
import IconGithub from "~/components/Icons/IconGithub.vue";
import IconLinkedin from "~/components/Icons/IconLinkedin.vue";
import IconInstagram from "~/components/Icons/IconInstagram.vue";
import IconYoutube from "~/components/Icons/IconYoutube.vue";
import IconItchio from "../Icons/IconItchio.vue";
export default {
  name: "CardLinks",
  components: {
    Card,
    IconGithub,
    IconLinkedin,
    IconInstagram,
    IconYoutube,
    IconItchio,
  },
};
</script>

<style>
</style>
