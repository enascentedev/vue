<script setup>
import Cabecalho from "../components/cabecalho.vue";
import Count from "../components/count.vue";
import Dashboard from "../components/dashboard.vue";
import Navegation from "../components/navegation.vue";
</script>

<template>
  <div class="flex h-screen">
    <aside class="w-1/5 h-full bg-red-600">
      <navegation />
    </aside>
    <main class="w-4/5 h-screen flex flex-col">
      <section class="h-20 bg-blue-500">
        <cabecalho />
      </section>
      <section class="h-40 bg-green-500">
        <count />
      </section>
      <section class="flex-1 bg-purple-500">
        <dashboard />
      </section>
    </main>
  </div>
</template>
