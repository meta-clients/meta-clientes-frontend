<template>
    <div class="form">
        <form action="post">
            <div class="input__group">
              <label class="input__group--label" for="name">Nome completo</label>
              <input class="input__group--input" type="text" placeholder="Nome completo" name="name" id="name">
            </div>
            <div class="input__group">
              <label class="input__group--label" for="email">E-mail</label>
              <input class="input__group--input" type="text" placeholder="example@example.com.br" name="email" id="email">
            </div>
            <div class="input__group">
              <label class="input__group--label" for="phone">Telefone</label>
              <input class="input__group--input" type="text" placeholder="(XX)xxxxx-xxxx" name="phone" id="phone">
            </div>
            <div class="input__group">
              <label class="input__group--label" for="bithdate">Data de nascimento</label>
              <input class="input__group--input" type="date" name="bithdate" id="bithdate">
            </div>
            <div class="input__group--checkbox">
              <input class="input__group--input-checkbox" type="checkbox" name="has_child" id="has_child">
              <label class="input__group--label" for="has_child">Possui filhos ?</label>
            </div>
            <div class="input__group">
              <label class="input__group--label" for="number_of_children">Quantidade</label>
              <input class="input__group--input input__group--number" type="number" name="number_of_children" id="number_of_children" min="1" max="5">
            </div>
        </form>
    </div>
</template>

<script>
export default {

}
</script>
