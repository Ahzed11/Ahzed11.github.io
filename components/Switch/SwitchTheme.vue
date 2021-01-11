<template>
  <div class="flex justify-between items-center" @click="toggleTheme">
    <div
      class="w-14 h-8 flex items-center bg-yellow-200 rounded-full p-1 duration-300 ease-in-out"
    >
      <div
        class="bg-gray-50 w-6 h-6 rounded-full transform duration-300 ease-in-out"
        :class="{ 'bg-gray-900 translate-x-6': toggleActive }"
      ></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SwitchTheme",
  data() {
    return {
      toggleActive: false,
    };
  },
  mounted() {
    if (this.$colorMode.value === "dark") {
      this.toggleActive = true;
    }
  },
  methods: {
    toggleTheme() {
      this.toggleActive = !this.toggleActive;
      if (this.toggleActive) {
        this.$colorMode.preference = "dark";
      } else {
        this.$colorMode.preference = "light";
      }
    },
  },
};
</script>