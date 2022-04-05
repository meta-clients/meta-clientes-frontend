<template>
  <nav class="sidebar">
    <img src="../assets/images/logo.svg" alt="Logo da Meta Clientes" class="sidebar__logo"/>
    <NuxtLink to="/">
      <span @click="closeMenu" href="#" class="sidebar__link sidebar__link--home sidebar__link--active">Início</span>
    </NuxtLink>
    <NuxtLink to="/mailling">
        <span @click="closeMenu" class="sidebar__link sidebar__link--mailling">Mailling</span>
    </NuxtLink>
    <NuxtLink to="/clientes">
       <span @click="closeMenu" class="sidebar__link sidebar__link--create-client">Cadastro</span>
    </NuxtLink>
  </nav>
</template>

<script>
export default {
    methods: {
        closeMenu: function(event) {
            const sidebar = document.querySelector('.sidebar');
            sidebar.classList.remove('sidebar--active')

            const menuAtual = document.querySelector('.sidebar__link--active')
            menuAtual.classList.remove('sidebar__link--active');

            const menuActive = event.target
            menuActive.classList.add('sidebar__link--active')
        }
    }
}
</script>
