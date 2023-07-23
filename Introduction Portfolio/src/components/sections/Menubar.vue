<script setup>
  import PortfolioContainerTutorial from '../PortfolioContainerTutorial.vue';
</script>

<template>
  <div
  class="text-center position-fixed"
  style="
      padding-top: 110px;
      width: 60px;
      height: 1000%;
      background: linear-gradient(to right, #24292c 90%,#34474D 10%);
      box-shadow: 10px 0px 50px 10px rgba(0, 0, 0, 0.5);
    "
  >
  <div>
      <!-- home button icon -->
        <div class="py-4">
          <span class="material-symbols-outlined"
            ><a
              id="transition"
              href="#"
              class="link-offset-2 link-underline link-underline-opacity-0"
              >
              home
            </a></span
            >
          </div>
  
        <!-- widgets button icon -->
        <div class="py-4">
          <span class="material-symbols-outlined"
            ><a
              id="transition"
              href="#"
              class="link-offset-2 link-underline link-underline-opacity-0"
            >
              widgets
            </a></span
          >
        </div>
  
        <!-- game button icon -->
        <div class="py-4">
          <span class="material-symbols-outlined"
            ><a
              id="transition"
              href="#"
              class="link-offset-2 link-underline link-underline-opacity-0"
            >
              videogame_asset
            </a></span
          >
        </div>
      </div>
    </div>
</template>

<style scoped>
#transition {
  color: rgb(220, 220, 220);
}
</style>
