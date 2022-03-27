<template>
  <div>
    <div class="page__wrapper">
    <header class="header">
        <button class="header__menu" aria-label="Menu"><i></i></button>
        <img src="../assets/images/logo.svg" alt="Logo da Meta Clientes" class="header__logo">
        <span class="header__profile--name">Josias Fernandes</span>
        <button class="header__profile--btn" aria-label="Menu do usuário"><i></i></button>
    </header>
    <section class="section__sidebar">
        <Sidebar />
    </section>
    <section class="section__onboard">
        <Nuxt />
    </section>
  </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
