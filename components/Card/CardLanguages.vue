<template>
  <card title="Languages">
    <list class="p-4">
      <list-element title="French">Native Language</list-element>
      <list-element title="English" />
      <list-element title="Japanese">JLPT N4</list-element>
    </list>
  </card>
</template>

<script>
import Card from "~/components/Card/Card.vue";
import List from "~/components/List/List.vue";
import ListElement from "~/components/List/ListElement.vue";
export default {
  name: "CardLanguages",
  components: {
    Card,
    List,
    ListElement,
  },
};
</script>

<style>
</style>
