<template>
  <footer class="bg-[#2c383f] pt-14 relative">
    <div class="container">
      <div class="grid grid-cols-5 font-medium pb-10">
        <!-- Course by series -->
        <div>
          <h3 class="text-xl mb-4 text-white">Course by Series</h3>
          <ul class="space-y-2">
            <li>
              <a class="footer-link" href="#">Laravel</a>
            </li>
            <li>
              <a class="footer-link" href="#">PHP</a>
            </li>
            <li>
              <a class="footer-link" href="#">Livewire</a>
            </li>
            <li>
              <a class="footer-link" href="#">Vue.js</a>
            </li>
          </ul>
        </div>

        <!-- Course by duration -->
        <div>
          <h3 class="text-xl mb-4 text-white">Course by Duration</h3>
          <ul class="space-y-2">
            <li>
              <a class="footer-link" href="#">1-5 hours</a>
            </li>
            <li>
              <a class="footer-link" href="#">5-10 hours</a>
            </li>
            <li>
              <a class="footer-link" href="#">10+ hours</a>
            </li>
          </ul>
        </div>

        <!-- Course by level -->
        <div>
          <h3 class="text-xl mb-4 text-white">Course by Level</h3>
          <ul class="space-y-2">
            <li>
              <a class="footer-link" href="#">Beginner</a>
            </li>
            <li>
              <a class="footer-link" href="#">Intermediate</a>
            </li>
            <li>
              <a class="footer-link" href="#">Advanced</a>
            </li>
          </ul>
        </div>

        <!-- Course by Platform -->
        <div>
          <h3 class="text-xl mb-4 text-white">Course by Platform</h3>
          <ul class="space-y-2">
            <li>
              <a class="footer-link" href="#">Laracasts</a>
            </li>
            <li>
              <a class="footer-link" href="#">Laravel Daily</a>
            </li>
            <li>
              <a class="footer-link" href="#">Codecourse</a>
            </li>
            <li>
              <a class="footer-link" href="#">Spatie</a>
            </li>
          </ul>
        </div>

        <!-- Course by Topics -->
        <div>
          <h3 class="text-xl mb-4 text-white">Course by Topics</h3>
          <ul class="space-y-2">
            <li>
              <a class="footer-link" href="#">Eloquent</a>
            </li>
            <li>
              <a class="footer-link" href="#">Validation</a>
            </li>
            <li>
              <a class="footer-link" href="#">Refactoring</a>
            </li>
            <li>
              <a class="footer-link" href="#">Testing</a>
            </li>
          </ul>
        </div>
      </div>
      <div class="pb-9 flex items-center justify-between">
        <ul>
          <li>
            <a href="https://twitter.com/dvlprJobayer" target="_blank">
              <svg
                class="hover:filter hover:brightness-200"
                xmlns="http://www.w3.org/2000/svg"
                width="15"
                height="12"
                fill="none"
              >
                <path
                  fill="#898F92"
                  d="M15 1.412a6.217 6.217 0 0 1-1.764.487 3.043 3.043 0 0 0 1.348-1.68c-.595.353-1.255.6-1.95.741C12.067.353 11.27 0 10.368 0 8.683 0 7.306 1.355 7.306 3.028c0 .24.03.473.08.692A8.79 8.79 0 0 1 1.045.558a2.96 2.96 0 0 0-.415 1.517c0 1.052.538 1.984 1.37 2.513a3.08 3.08 0 0 1-1.399-.353v.021c0 1.469 1.061 2.697 2.467 2.972a3.072 3.072 0 0 1-1.384.05 3.023 3.023 0 0 0 1.09 1.505 3.1 3.1 0 0 0 1.778.598A6.171 6.171 0 0 1 .731 10.68c-.243 0-.487-.014-.731-.042A8.808 8.808 0 0 0 4.718 12c5.65 0 8.755-4.616 8.755-8.619 0-.134 0-.261-.007-.395A6.094 6.094 0 0 0 15 1.412Z"
                ></path>
              </svg>
            </a>
          </li>
        </ul>
        <p class="text-[#898F92] text-sm font-medium">
          Developed by
          <a
            class="font-bold hover:underline"
            href="https://github.com/dvlprJobayer"
            target="_blank"
            >Jobayer Ahammed Patwary ??????</a
          >
        </p>
        <span></span>
      </div>
    </div>
    <img
      class="absolute right-0 bottom-0"
      src="../assets/img/footer.png"
      alt="Footer Image"
    />
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
};
</script>

<style>
.footer-link {
  @apply border-b-2 border-transparent hover:border-[#ff5f53] transition duration-300 ease-linear text-gray-300;
}
</style>
