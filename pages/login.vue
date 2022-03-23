<template>
    <div class="container">
      <div class="logo">
        <!-- <span>Logo do cliente</span> -->
      </div>
      <form class="container__form" action="">
        <div class="input__group">
          <div class="label__group">
            <img src="../assets/images/user.svg" alt="">
            <label for="user">Usuário</label>
          </div>
          <input type="text" name="user" id="user">
        </div>
        <div class="input__group">
          <div class="label__group">
              <img src="../assets/images/lock.svg" alt="">
              <label for="password">Senha</label>
          </div>
          <input type="password" name="password" id="password">
        </div>
        <div class="footer__form">
          <span class="forgot__password"><a href="#">Esqueceu a senha?</a></span>
          <button class="btn-submit" type="submit">Entrar</button>
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
      background-color: #EDF2F7;

      &__form {
        text-align: center;
        border-radius: 10px;
        padding: 25px 10px 25px 10px;
        background-color: #FFFFFF;
        box-sizing: border-box;
      }

      &__form input {
          background-color: #EDF2F7;
          border-radius: 5px;
          padding: 10px;
      }

      .input__group {
          display: flex;
          flex-direction: column;
          align-items: flex-start;
          padding: 5px;
      }

      .label__group {
          display: flex;
          padding: 5px;
          font-size: 17px;
          color: #2A4365
      }

      .label__group img{
          width: 15px;
          margin-right: 5px;
          margin-bottom: 5px;
      }

      .footer__form {
          display: flex;
          justify-content: space-around;
          margin-top: 10px;

          .forgot__password {
            font-size: 12px;
            color: #3182CE;
            text-decoration: underline;
            align-self: center;
          }

          .btn-submit {
            color: #fff;
            background: #2A4365;
            border-radius: 5px;
            box-sizing: border-box;
            padding: 10px 20px 10px 20px;
            width: 45%;
          }
      }
    }
</style>
