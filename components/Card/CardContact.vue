<template>
  <card title="Contact">
    <form
      class="flex flex-col px-4 pt-6 pb-4 flex-grow"
      name="contact"
      method="POST"
    >
      <label for="email" class="font-semibold text-lg dark:text-white"
        >Email</label
      >
      <input
        type="email"
        id="email"
        name="email"
        class="border rounded-md shadow-inner"
      />
      <label for="body" class="font-semibold text-lg mt-2 dark:text-white"
        >Your message</label
      >
      <textarea name="body" class="border rounded-md shadow-inner flex-grow" />
      <button
        type="submit"
        class="mt-4 p-2 rounded-md font-light shadow-inner bg-purple-800 text-white dark:bg-green-300 dark:text-black transform hover:scale-95 transition duration-300"
      >
        Contact me
      </button>
    </form>
  </card>
</template>

<script>
import Card from "~/components/Card/Card.vue";
export default {
  name: "CardContact",
  components: {
    Card,
  },
};
</script>

<style>
</style>
