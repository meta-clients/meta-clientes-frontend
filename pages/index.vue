<template>
<div class="page__wrapper">
    <header class="header">
        <button class="header__menu" aria-label="Menu"><i></i></button>
        <img src="../assets/images/logo.svg" alt="Logo da Meta Clientes" class="header__logo">
        <span class="header__profile--name">Josias Fernandes</span>
        <button class="header__profile--btn" aria-label="Menu do usuário"><i></i></button>
    </header>
    <div class="sidebar">
        <nav>
          <ul>
            <li><a href="#">Mailling</a></li>
            <li><a href="#">Cadastro</a></li>
          </ul>
        </nav>
    </div>
    <div class="onboard">
        <div>
            <span>Onboard</span>
        </div>
    </div>
</div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

// <style lang="scss">
//     .page__wrapper {
//         width: inherit;
//     }
// </style>
