<template>
  <!-- Hero Section -->
  <div class="flex hero-min-h items-center justify-center text-center">
    <div class="max-w-[850px] mx-auto relative">
      <h1 class="my-6 text-[52px] leading-none font-bold text-[#222]">
        The best Courses and Books on the
        <span class="text-[#ff5f53]">Laravel</span> ecosystem
      </h1>
      <p class="text-lg mt-4 mb-10 text-gray-600 font-medium">
        Find the right books and courses on the Laravel framework and related
        topics to suite your level of expertise. Know how good a course is
        through your peers review and share your own too.
      </p>
      <form action="" class="flex w-[700px] mx-auto gap-x-6">
        <input
          class="border font-medium border-[#ff5f53] py-3 px-4 rounded-lg flex-1"
          type="text"
          name=""
          id=""
          placeholder="Enter keywords to search courses"
        />
        <button class="btn-primary">Search</button>
      </form>

      <!-- Icons -->
      <img
        src="https://laravel-courses.com/img/left-top-angle.png"
        alt="angle"
        class="absolute pointer-events-none top-[70px] -left-28"
      />
      <img
        src="https://laravel-courses.com/img/left-bottom-angle.png"
        alt="angle"
        class="absolute pointer-events-none top-[280px] -left-12"
      />
      <img
        src="https://laravel-courses.com/img/right-angle.png"
        alt="angle"
        class="absolute pointer-events-none top-0 -right-10"
      />
      <img
        src="https://laravel-courses.com/img/right-center-angle.png"
        alt="angle"
        class="absolute pointer-events-none top-[140px] -right-52"
      />
      <img
        src="https://laravel-courses.com/img/right-bottom-angle.png"
        alt="angle"
        class="absolute pointer-events-none top-[270px] -right-24"
      />
    </div>
  </div>

  <!-- Logo Section -->
  <ul class="container pb-28 flex gap-x-8 justify-center">
    <li
      class="border border-[#ff5f53] h-16 w-full rounded-lg flex items-center justify-center shadow"
    >
      <img src="../assets/img/laravel.png" alt="" />
    </li>
    <li
      class="border border-[#ff5f53] h-16 w-full rounded-lg flex items-center justify-center shadow"
    >
      <img src="../assets/img/php.png" alt="" />
    </li>
    <li
      class="border border-[#ff5f53] h-16 w-full rounded-lg flex items-center justify-center shadow"
    >
      <img src="../assets/img/livewire.png" alt="" />
    </li>
    <li
      class="border border-[#ff5f53] h-16 w-full rounded-lg flex items-center justify-center shadow"
    >
      <img src="../assets/img/vue.png" alt="" />
    </li>
    <li
      class="border border-[#ff5f53] h-16 w-full rounded-lg flex items-center justify-center shadow"
    >
      <img src="../assets/img/alphine.png" alt="" />
    </li>
    <li
      class="border border-[#ff5f53] h-16 w-full rounded-lg flex items-center justify-center shadow"
    >
      <img src="../assets/img/tailwind.png" alt="" />
    </li>
  </ul>

  <!-- Featured Courses -->
  <section class="container">
    <h2 class="text-center text-[2.25rem] text-[#2c383f] font-bold mb-12">
      Featured Courses
    </h2>

    <!-- Feature Courses -->
    <div class="grid grid-cols-3 gap-12">
      <!-- Single Course Card 1 -->
      <div class="shadow-lg">
        <img src="../assets/img/php-everyone.png" alt="PHP for everyone" />
        <div class="px-6 py-8">
          <h2 class="text-xl text-[#4c555a] font-semibold">PHP For Everyone</h2>
          <div class="flex my-4 items-center gap-x-2">
            <img
              class="rounded-full"
              src="../assets/img/joffery.png"
              alt="joffery"
            />
            <p class="text-[#4c555a] font-medium">Jeffrey Way</p>
          </div>
          <div class="flex items-center gap-x-3">
            <p
              class="flex items-center gap-x-2 text-[#4c555a] font-medium bg-[#ebfff3] px-2 py-1 rounded-[3px]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                width="15"
                height="15"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z"
                />
              </svg>
              <span>04 h 05 min</span>
            </p>
            <p
              class="flex items-center gap-x-2 text-[#4c555a] font-medium bg-[#ebf1ff] px-2 py-1 rounded-[3px]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                width="15"
                height="15"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 013 19.875v-6.75zM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V8.625zM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V4.125z"
                />
              </svg>

              <span>Intermediate</span>
            </p>
          </div>
        </div>
      </div>
      <!-- Single Course Card 2 -->
      <div class="shadow-lg">
        <img src="../assets/img/pest-laravel.png" alt="PEST Driven Laravel" />
        <div class="px-6 py-8">
          <h2 class="text-xl text-[#4c555a] font-semibold">
            PEST Driven Laravel
          </h2>
          <div class="flex my-4 items-center gap-x-2">
            <img
              class="rounded-full"
              src="../assets/img/rumpel.png"
              alt="Christoph Rumpel"
            />
            <p class="text-[#4c555a] font-medium">Christoph Rumpel</p>
          </div>
          <div class="flex items-center gap-x-3">
            <p
              class="flex items-center gap-x-2 text-[#4c555a] font-medium bg-[#ebfff3] px-2 py-1 rounded-[3px]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                width="15"
                height="15"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z"
                />
              </svg>
              <span>06 h 17 min</span>
            </p>
            <p
              class="flex items-center gap-x-2 text-[#4c555a] font-medium bg-[#ebf1ff] px-2 py-1 rounded-[3px]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                width="15"
                height="15"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 013 19.875v-6.75zM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V8.625zM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V4.125z"
                />
              </svg>

              <span>Intermediate</span>
            </p>
          </div>
        </div>
      </div>
      <!-- Single Course Card 3 -->
      <div class="shadow-lg">
        <img src="../assets/img/testing-laravel.png" alt="Testing Laravel" />
        <div class="px-6 py-8">
          <h2 class="text-xl text-[#4c555a] font-semibold">Testing Laravel</h2>
          <div class="flex my-4 items-center gap-x-2">
            <img
              class="rounded-full"
              src="../assets/img/freek.png"
              alt="Freek Van der Herten"
            />
            <p class="text-[#4c555a] font-medium">Freek Van der Herten</p>
          </div>
          <div class="flex items-center gap-x-3">
            <p
              class="flex items-center gap-x-2 text-[#4c555a] font-medium bg-[#ebfff3] px-2 py-1 rounded-[3px]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                width="15"
                height="15"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z"
                />
              </svg>
              <span>06 h 00 min</span>
            </p>
            <p
              class="flex items-center gap-x-2 text-[#4c555a] font-medium bg-[#ebf1ff] px-2 py-1 rounded-[3px]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                width="15"
                height="15"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 013 19.875v-6.75zM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V8.625zM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V4.125z"
                />
              </svg>

              <span>Intermediate</span>
            </p>
          </div>
        </div>
      </div>
      <!-- Single Course Card 4 -->
      <div class="shadow-lg">
        <img
          src="../assets/img/laravel-security.png"
          alt="Practical Laravel Security"
        />
        <div class="px-6 py-8">
          <h2 class="text-xl text-[#4c555a] font-semibold">
            Practical Laravel Security
          </h2>
          <div class="flex my-4 items-center gap-x-2">
            <img
              class="rounded-full"
              src="../assets/img/stephen.png"
              alt="Stephen Rees-Carter"
            />
            <p class="text-[#4c555a] font-medium">Stephen Rees-Carter</p>
          </div>
          <div class="flex items-center">
            <p
              class="flex items-center gap-x-2 text-[#4c555a] font-medium bg-[#ebf1ff] px-2 py-1 rounded-[3px]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                width="15"
                height="15"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 013 19.875v-6.75zM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V8.625zM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V4.125z"
                />
              </svg>

              <span>Intermediate</span>
            </p>
          </div>
        </div>
      </div>
      <!-- Single Course Card 5 -->
      <div class="shadow-lg">
        <img
          src="../assets/img/laravel-que.png"
          alt="Laravel Queues in Action"
        />
        <div class="px-6 py-8">
          <h2 class="text-xl text-[#4c555a] font-semibold">
            Laravel Queues in Action
          </h2>
          <div class="flex my-4 items-center gap-x-2">
            <img
              class="rounded-full"
              src="../assets/img/said.png"
              alt="Mohamed Said"
            />
            <p class="text-[#4c555a] font-medium">Mohamed Said</p>
          </div>
          <div class="flex items-center">
            <p
              class="flex items-center gap-x-2 text-[#4c555a] font-medium bg-[#ebf1ff] px-2 py-1 rounded-[3px]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                width="15"
                height="15"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 013 19.875v-6.75zM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V8.625zM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V4.125z"
                />
              </svg>

              <span>Intermediate</span>
            </p>
          </div>
        </div>
      </div>
      <!-- Single Course Card 6 -->
      <div class="shadow-lg">
        <img src="../assets/img/php-everyone.png" alt="PHP for everyone" />
        <div class="px-6 py-8">
          <h2 class="text-xl text-[#4c555a] font-semibold">PHP For Everyone</h2>
          <div class="flex my-4 items-center gap-x-2">
            <img
              class="rounded-full"
              src="../assets/img/joffery.png"
              alt="joffery"
            />
            <p class="text-[#4c555a] font-medium">Jeffrey Way</p>
          </div>
          <div class="flex items-center gap-x-3">
            <p
              class="flex items-center gap-x-2 text-[#4c555a] font-medium bg-[#ebfff3] px-2 py-1 rounded-[3px]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                width="15"
                height="15"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z"
                />
              </svg>
              <span>04 h 05 min</span>
            </p>
            <p
              class="flex items-center gap-x-2 text-[#4c555a] font-medium bg-[#ebf1ff] px-2 py-1 rounded-[3px]"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                width="15"
                height="15"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 013 19.875v-6.75zM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V8.625zM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V4.125z"
                />
              </svg>

              <span>Intermediate</span>
            </p>
          </div>
        </div>
      </div>
    </div>

    <!-- Featured Courses Button -->
    <div class="my-10 text-center">
      <button class="btn-primary">Browse All</button>
    </div>
  </section>

  <!-- Newsletter Section -->
  <section class="bg-[#fff7f6] h-96 flex items-center">
    <div class="container flex items-center justify-between">
      <div class="w-1/2">
        <h2 class="text-4xl text-[#ff5f53] font-bold">
          Don&#39;t miss any updates
        </h2>
        <p class="text-[#4c555a] font-medium mt-6">
          We will be covering course reviews, comparison between the best
          courses, and will be sharing exclusive discounts with you on a monthly
          basis.
        </p>
        <form class="flex items-center mt-12 gap-x-4">
          <input
            placeholder="Your Email Address"
            type="email"
            name=""
            id=""
            class="bg-white flex-1 px-4 py-3 text-lg font-medium rounded-lg border border-[#ff5f53]"
          />
          <input
            type="submit"
            value="Subscribe"
            class="text-lg font-medium text-[#ff5f53] border border-[#ff5f53] px-6 py-3 rounded-lg cursor-pointer hover:bg-[#ff5f53] hover:text-white transition duration-300 ease-in-out"
          />
        </form>
      </div>
      <img src="../assets/img/mail.png" alt="Mail" />
    </div>
  </section>
</template>

<script>
export default {
  name: "HomeView",
};
</script>

<style scoped>
.hero-min-h {
  min-height: calc(100vh - 60px);
}
</style>
