<script setup>
import Menubar from "./sections/Menubar.vue";
import SearchBar from "./sections/SearchBar.vue";
import Content from "./sections/Content.vue";
import DetailButton from "./sections/DetailButton.vue"
import FooterBar from "./sections/FooterBar.vue";
</script>

<template>
  <div>
    <DetailButton />
    <Menubar />
    <Content />
    <SearchBar />
    <FooterBar />
  </div>
</template>
