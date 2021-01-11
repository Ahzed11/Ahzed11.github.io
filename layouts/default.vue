<template>
  <div class="bg-gray-100 dark:bg-gray-800">
    <div class="flex flex-row-reverse pt-2 mx-auto">
      <switch-theme></switch-theme>
    </div>
    <Nuxt />
  </div>
</template>

<script>
import SwitchTheme from "~/components/Switch/SwitchTheme.vue";
export default {
  components: { SwitchTheme },
};
</script>

<style>
</style>
