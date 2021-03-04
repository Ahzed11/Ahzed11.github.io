<template>
  <card title="Skills">
    <list class="p-4">
      <list-element title="PHP">Symfony</list-element>
      <list-element title="Javascript">Vue, Nuxt, Express</list-element>
      <list-element title="Python">
        <a
          class="hover:text-purple-800 dark:hover:text-green-300"
          href="https://uclouvain.be/en-cours-2020-linfo1101"
          target="_blank"
          >Uni's course</a
        >, some Flask, some Discord.py
      </list-element>
      <list-element title="Java">
        <a
          class="hover:text-purple-800 dark:hover:text-green-300"
          href="https://uclouvain.be/en-cours-2020-lepl1402"
          target="_blank"
          >Uni's course</a
        >
      </list-element>
    </list>
  </card>
</template>

<script>
import Card from "~/components/Card/Card.vue";
import List from "~/components/List/List.vue";
import ListElement from "~/components/List/ListElement.vue";
export default {
  name: "CardSkills",
  components: {
    Card,
    List,
    ListElement,
  },
};
</script>

<style>
</style>
