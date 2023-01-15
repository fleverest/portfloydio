<template>
  <div
    bg="gradient-to-br"
    from="gray-700"
    to="gray-900"
    h="screen"
    class="flex flex-col"
  >
    <Header />

    <transition name="fade" mode="out-in">
      <Nuxt />
    </transition>

    <Footer />
  </div>
</template>

<script lang="ts">
import Header from '../components/Header.vue';
import Footer from '../components/Footer.vue';
<script>
