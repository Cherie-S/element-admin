<template>
  <div class="login">
    <div class="login-con">
      <login-form></login-form>
    </div>
  </div>
</template>

<script>
  import LoginForm from '@/components/login/login-form'
  export default {
    name: 'index',
    components: {
      'login-form': LoginForm
    }
  }
</script>

<style scoped>
  .login {
    width: 100%;
    height: 100%;
    background-image: url('../../assets/images/login-bg.jpg');
    background-size: cover;
    background-position: center;
    position: relative;
  }
  .login-con{
    position: absolute;
    right: 20%;
    top: 55%;
    transform: translateY(-60%);
    width: 300px;
  }
</style>
