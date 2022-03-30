<template>
  <main class="mailling">
        <div class="mailling__header">
            <h2 class="mailling__title">Mailling</h2>
            <button class="mailling__create">
              <NuxtLink to="/clientes/create">
                +Criar
              </NuxtLink>
            </button>
        </div>
        <NuxtChild />
  </main>
</template>

<script>
export default {

}
</script>

<style>

</style>
