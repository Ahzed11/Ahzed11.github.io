<template>
  <div class="mx-auto md:w-2/5 sm:w-auto pt-8 pb-16">
    <img
      class="mx-auto rounded-full w-32 h-32 shadow-lg"
      src="/images/me.png"
    />
    <h1 class="text-3xl mt-4 font-semibold text-center dark:text-white">
      Alexandre Zenon
    </h1>
    <h2 class="font-light text-center dark:text-white">
      Killing my time developping websites
    </h2>
    <h3 class="font-light text-center dark:text-white">
      CS Student at UCLouvain
    </h3>
    <div class="flex flex-row justify-center mt-4">
      <pill body="Contact Me" bgClass="bg-purple-800" has-text-white />
      <!--<pill body="Want to offer me a coffee?" bgClass="bg-green-300" />-->
    </div>

    <div class="grid md:grid-cols-2 sm:grid-cols-1 gap-4 mt-6">
      <card-about-me />
      <card-contact />

      <card-skills />
      <card-projects />

      <card-languages />
      <card-links />
    </div>
  </div>
</template>

<script>
import CardAboutMe from "~/components/Card/CardAboutMe.vue";
import CardContact from "~/components/Card/CardContact.vue";
import CardLanguages from "~/components/Card/CardLanguages.vue";
import CardLinks from "~/components/Card/CardLinks.vue";
import CardProjects from "~/components/Card/CardProjects.vue";
import CardSkills from "~/components/Card/CardSkills.vue";
import Pill from "~/components/Pill/Pill.vue";
export default {
  head() {
    return {
      title: "Alexandre Zenon",
    };
  },
  components: {
    CardAboutMe,
    CardLanguages,
    CardLinks,
    CardProjects,
    Pill,
    CardSkills,
    CardContact,
  },
};
</script>

<style>
</style>
