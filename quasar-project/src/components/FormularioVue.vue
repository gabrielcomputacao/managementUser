<template>
  <div class="q-pa-md" style="min-width: 500px ;">
    <q-form>
      <div class="row justify-center">
        <q-input class="inputText" filled v-model="textoBusca" label="Digite o nome ou email" />
        <q-btn label="Submit" type="submit" color="primary" />

      </div>
    </q-form>
  </div>
</template>

<script lang="ts">
import { ref, defineComponent } from 'vue'
const textoBusca = ref('')
export default defineComponent({
  setup () {
    return {
      textoBusca
    }
  }
})
</script>

<style scoped>
  .inputText{
    width: 100%;
    margin-bottom: 1rem;
  }

</style>
