<script>
  import LoginUser from '../components/LoginUser.vue'
  export default { components: { LoginUser } }
</script>

<template>
  <h1>Sign In</h1>
  <LoginUser />
</template>

<style lang="scss" scoped>
  h1 {
    text-align: center;
    color: #fff;
    width: 20%;
    margin: 20% 40% 5% 40%;
  }
  p {
    color: #fff;
    width: 10%;
    margin: 1rem 45% 0 45%;
    text-align: center;
  }
</style>
