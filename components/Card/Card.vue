<template>
  <article
    class="rounded-xl bg-white shadow-md dark:bg-gray-900 flex flex-col transform hover:scale-105 transition duration-300"
  >
    <h1 class="text-2xl font-semibold pt-4 pb-1 px-4 dark:text-white">
      {{ title }}
    </h1>
    <hr class="w-1/5 ml-4 pb-1 rounded-xl bg-purple-800 dark:bg-green-300" />
    <slot></slot>
  </article>
</template>

<script>
export default {
  name: "Card",
  props: {
    title: {
      type: String,
      required: true,
    },
  },
};
</script>