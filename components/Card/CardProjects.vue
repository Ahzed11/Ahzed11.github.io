<template>
  <card title="Projects">
    <list class="p-4">
      <list-element
        title="Communoté"
        description="Note sharing website for college students"
        link="https://www.communote.be/"
      />
      <list-element
        title="Dick Guigui"
        description="A small game made on godot for a Game Jam"
        link="https://ahzed.itch.io/dick-guigui"
      />
      <list-element
        title="APPSINF"
        description="A site where you can post articles written in Markdown. It was made for a university class about creating a website. It is unfinished."
        link="https://github.com/Ahzed11/APPSINF"
      />
      <list-element
        title="Japan Blog"
        description="My blog about my exchange in Japan"
      />
    </list>
  </card>
</template>

<script>
import Card from "~/components/Card/Card.vue";
import List from "~/components/List/List.vue";
import ListElement from "~/components/List/ListElement.vue";
export default {
  name: "CardProjects",
  components: {
    Card,
    List,
    ListElement,
  },
};
</script>

<style>
</style>
