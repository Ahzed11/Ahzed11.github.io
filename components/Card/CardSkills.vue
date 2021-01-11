<template>
  <card title="Skills">
    <list class="p-4">
      <list-element title="PHP" description="Symfony" />
      <list-element title="Javascript" description="Vue, Nuxt, Express" />
      <list-element
        title="Python"
        description="Uni's exam, some Flask, some Discord.py"
      />
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
