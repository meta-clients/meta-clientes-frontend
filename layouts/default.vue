<template>
  <div>
    <div class="page__wrapper">
      <section class="section__header">
        <header class="header">
          <button class="header__menu" aria-label="Menu" v-on:click="showMenu"><i></i></button>
          <img src="../assets/images/logo.svg" alt="Logo da Meta Clientes" class="header__logo">
          <span class="header__profile--name">Josias Fernandes</span>
          <button class="header__profile--btn" aria-label="Menu do usuário"><i></i></button>
        </header>
      </section>
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
    methods: {
        showMenu: function(event) {
            var sidebar = document.querySelector('.sidebar');
            sidebar.classList.toggle('sidebar--active')
        }
    }
}
</script>

<style>

</style>
