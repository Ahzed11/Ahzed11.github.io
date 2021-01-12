<template>
  <card title="Projects">
    <list class="p-4">
      <list-element title="Communoté" link="https://www.communote.be/">
        Note sharing website for college students
      </list-element>
      <list-element
        title="Dick Guigui"
        link="https://ahzed.itch.io/dick-guigui"
      >
        A small game inspired by hotline miami made on godot for a Game Jam
      </list-element>
      <list-element title="APPSINF" link="https://github.com/Ahzed11/APPSINF">
        A website where you can post articles written in Markdown. It was made
        for a university class about creating a website. It is unfinished.
      </list-element>
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
