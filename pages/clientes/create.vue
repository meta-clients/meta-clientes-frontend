<template>
    <div class="form">
        <form action="post">
            <div class="input__group">
              <label for="name">Nome completo</label>
              <input type="text" placeholder="Nome completo" name="name" id="name">
            </div>
            <div class="input__group">
              <label for="email">E-mail</label>
              <input type="text" placeholder="example@example.com.br" name="email" id="email">
            </div>
            <div class="input__group">
              <label for="phone">Telefone</label>
              <input type="text" placeholder="(XX)xxxxx-xxxx" name="phone" id="phone">
            </div>
            <div class="input__group">
              <label for="bithdate">Data de nascimento</label>
              <input type="date" name="bithdate" id="bithdate">
            </div>
            <div class="input__group">
              <label for="has_child">Possui filhos ?</label>
              <input type="checkbox" name="has_child" id="has_child">
            </div>
            <div class="input__group">
              <label for="number_of_children">Quantidade</label>
              <input type="number" name="number_of_children" id="number_of_children" min="1">
            </div>
        </form>
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
