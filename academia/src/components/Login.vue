<template>
  <div class="container">
    <img class="wave" src="img/wave.png" />

    <div class="img">
      <img alt="Academia Logo" src="../assets/img/undraw_fitness_tracker_3033.svg" />
    </div>
    <div class="login-content">
      <form @submit="logar()">
        <img src="../assets/img/avatar.svg" alt="Avatar Usuario" />
        <h2 class="title">Bem-Vindo</h2>
        <div class="input-div one">
          <div class="i">
            <i class="fas fa-user"></i>
          </div>
          <div class="div">
            <h5>Username</h5>
            <input type="text" class="input" />
          </div>
          <div class="input-div pass">
            <div class="i">
              <i class="fas fa-lock"></i>
            </div>
            <div class="div">
              <h5>Password</h5>
              <input type="password" class="input" />
            </div>
          </div>
          <a href="#">Forgot Password?</a>
          <input type="submit" class="btn" value="Login" />
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "Index",
  props: {
    msg: String
  }
};
</script>

<style>
</style>
