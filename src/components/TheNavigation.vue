<template>
  <nav id="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/brazil">Brazil</router-link>
    <router-link to="/panama">Panama</router-link>
    <router-link to="/hawaii">Hawaii</router-link>
    <router-link to="/jamaica">Jamaica</router-link>
  </nav>
</template>

<script>
export default {
name: "TheNavigation"
}
</script>

<style scoped lang="scss">
#nav{
  display: flex;
  justify-content: center;
  & a{
    padding: 0 16px;
    color: #2c3e50;

    &.router-link-exact-active{
      color: #42b983;
    }
  }
}
</style>
