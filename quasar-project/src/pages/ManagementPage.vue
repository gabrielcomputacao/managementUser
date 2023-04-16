<template>
  <q-page class="column items-center justify-center">
    <div class="bg-light-blue-4" style="width: 400px;height: auto;">
      <q-img src="../assets/img/onfly-header.svg" />
    </div>
    <h3>Gestão de Usuários</h3>
    <div>
      <FormularioVue />
    </div>
  </q-page>
</template>

<script setup lang="ts">
import FormularioVue from 'src/components/FormularioVue.vue'
</script>
