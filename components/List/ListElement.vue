<template>
  <li class="py-3">
    <component
      :is="!!link ? 'a' : 'div'"
      :href="link"
      target="_blank"
      :class="{
        'hover:text-purple-800 dark:hover:text-green-300': !!link,
      }"
    >
      <h2 class="text-lg font-semibold">
        {{ title }}
      </h2>
      <slot class="font-light text-justify"> </slot>
    </component>
  </li>
</template>

<script>
export default {
  name: "ListElement",
  props: {
    title: {
      required: true,
      type: String,
    },
    link: {
      required: false,
      type: String,
    },
  },
};
</script>