<template>
  <div class="app">
    <navbar />

    <middle-bar />

    <bawah />

    <company />
  </div>
</template>

<script>
import Navbar from "~/components/Navbar.vue";
import MiddleBar from "../components/MiddleBar.vue";
import Bawah from "../components/Bawah.vue";
import Company from "../components/Company.vue";

export default {
  components: { Navbar, MiddleBar, Bawah, Company },
};
</script>

<style></style>
