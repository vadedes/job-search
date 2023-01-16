<template>
  <header class="w-full text-sm">
    <div class="fixed top-0 left-0 h-16 w-full bg-white">
      <div class="mx-auto flex h-full flex-nowrap border-b border-solid">
        <a href="/" class="flex h-full items-center text-xl">
          {{ company }}
        </a>
        <h2 class="ml-8 flex h-full items-center">
          Developed by {{ author.firstName }} {{ author.lastName }}
        </h2>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "MainNav",
  // Below code allows components to hold data it must be named data(){} as shown below - data method
  data() {
    return {
      company: "Bobo Careers",
      author: {
        firstName: "Dave",
        lastName: "Frenz",
      },
    };
  },
};
</script>
