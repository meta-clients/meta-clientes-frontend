<template>
    <div class="container">
      <div class="logo">
        <span>Logo do cliente</span>
      </div>
      <form class="container__form" action="">
        <div class="input__group">
          <label for="user">Nome de usuário</label>
          <input type="text" name="user" id="user">
        </div>
        <div class="input__group">
          <label for="password">Nome de usuário</label>
          <input type="text" name="password" id="password">
        </div>
      </form>
    </div>
</template>

<script>
export default {
  name: 'LoginPage'
}
</script>

<style lang="scss">
    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;

      &__form {
        text-align: center;
        border: 1px solid #cecece;
        border-radius: 10px;
        padding: 15px;
      }
    }
</style>
