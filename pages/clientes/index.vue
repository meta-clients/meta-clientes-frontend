<template>
    <div>
      <Form
        :inputs='inputs'
      />
    </div>
</template>

<script>
export default {
    data() {
      return {
        'inputs': [
          {name: 'name', id: 'name', placeholder: 'Insira seu nome', label: 'Nome completo'},
          {name: 'email', id: 'email', placeholder: 'example@example.com.br', label: 'E-mail'},
          {name: 'phone', id: 'phone', placeholder: '(XX)xxxxx-xxxx', label: 'Telefone'},
          {name: 'birthdate', id: 'birthdate', label: 'Data de nascimento', type: 'date'},
          {name: 'has_child', id: 'has_child', label: 'Possui filhos?', type: 'checkbox'},
          {name: 'number_of_children', id: 'number_of_children', label: 'Quantidade', type: 'number'},
        ]
      }
    }
}
</script>

<style>

</style>
