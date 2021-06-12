<template>
  <card title="My links">
    <div class="grid grid-cols-4 gap-4 pt-5 pb-6 px-4 dark:text-white">
      <a
        class="rounded-xl shadow-md"
        href="https://www.linkedin.com/in/alexandre-zenon/"
        target="_blank"
      >
        <icon-linkedin />
      </a>
      <a
        class="rounded-xl shadow-md"
        href="https://github.com/Ahzed11/"
        target="_blank"
      >
        <icon-github />
      </a>
      <a
        class="rounded-xl shadow-md"
        href="https://www.youtube.com/channel/UCm0Tstopf2nxISi6bQ-WAiw"
        target="_blank"
      >
        <icon-youtube />
      </a>
      <a
        class="rounded-xl shadow-md"
        href="https://www.youtube.com/channel/UCm0Tstopf2nxISi6bQ-WAiw"
        target="_blank"
      >
        <icon-twitch />
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
        href="https://unsplash.com/@ahzed11"
        target="_blank"
      >
        <icon-unsplash />
      </a>
      <a
        class="rounded-xl shadow-md"
        href="https://www.buymeacoffee.com/ahzed11"
        target="_blank"
      >
        <icon-buy-me-a-coffee />
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
import IconUnsplash from "../Icons/IconUnsplash.vue";
import IconBuyMeACoffee from '../Icons/IconBuyMeACoffee.vue';
import IconTwitch from '../Icons/IconTwitch.vue';

export default {
  name: "CardLinks",
  components: {
    Card,
    IconGithub,
    IconLinkedin,
    IconInstagram,
    IconYoutube,
    IconItchio,
    IconUnsplash,
    IconTwitch,
  },
};
</script>

<style>
</,
    IconBuyMeACoffeestyle>
