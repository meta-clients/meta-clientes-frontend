<template>
  <article class="card__client">
      <div class="card__client__data">
        <h3 class="card__client__data--name">Roberda CuVerde</h3>
        <span class="card__client__data--email">roberda.cuverde@gmail.com</span>
      </div>
      <span class="card__client--gen">Gênero: Não binária(o)</span>
      <span class="card__client--birth">Aniversário: 22/05/2005</span>
      <div class="card__client__btn">
        <button class="card__client__btn--edit">
          <NuxtLink to="/clientes/update">
            Editar
          </NuxtLink>
        </button>
        <button class="card__client__btn--del">
          <NuxtLink to="/clientes/delete">
            Excluir
          </NuxtLink>
        </button>
      </div>
  </article>
</template>

<script>
export default {

}
</script>

<style>

</style>
