<template>
  <a
    class="rounded-full font-light py-1 px-4 shadow-md mr-2 transform hover:scale-105 transition duration-300 text-center"
    :class="`${bgClass} ${!!hasTextWhite ? 'text-white' : ''}`"
    :href="path"
  >
    {{ body }}
  </a>
</template>

<script>
export default {
  name: "Pill",
  props: {
    body: {
      type: String,
      required: true,
    },
    bgClass: {
      type: String,
      required: true,
    },
    path: {
      type: String,
      required: false,
    },
    hasTextWhite: {
      type: Boolean,
      required: false,
    },
  },
};
</script>