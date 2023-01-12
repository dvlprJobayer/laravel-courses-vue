<template>
  <header class="shadow-md border-gray-100">
    <div class="flex items-center justify-between container mx-auto">
      <div class="flex items-center gap-x-8">
        <router-link class="py-4" to="/">
          <img class="w-56" src="../assets/img/logo.png" alt="logo" />
        </router-link>
        <nav class="space-x-8 text-base font-medium text-gray-500">
          <router-link
            class="border-b-2 py-[18px] border-transparent hover:text-gray-700 hover:border-gray-300 focus:text-gray-700 focus:border-purple-400"
            to="/courses"
            >Courses</router-link
          >
          <router-link
            class="border-b-2 py-[18px] border-transparent hover:text-gray-700 hover:border-gray-300 focus:text-gray-700 focus:border-purple-400"
            to="/courses"
            >Books</router-link
          >
        </nav>
      </div>

      <!-- Login Signup Area -->
      <div class="space-x-8">
        <a href="#" class="text-base text-gray-500 font-medium">Sign in</a>
        <a class="text-white bg-black py-2 px-4 rounded font-medium" href="#"
          >Sign up</a
        >
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
};
</script>
