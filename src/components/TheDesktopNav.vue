<template>
  <section class="nav">
    <div class="nav-logo">
      <img src="../assets/vue.png" alt="logo" class="avatar" height="200px" />
    </div>
    <h1>This is the Desktop view</h1>
    <div class="nav-menu">
      <ul class="nav-menu-list">
        <router-link style="text-decoration : none; color: inherit;" to='/about'><li class="nav-list-item">About me</li></router-link>
        <router-link style="text-decoration : none; color: inherit;" to='/github'><li class="nav-list-item">CV</li></router-link>
        <router-link style="text-decoration : none; color: inherit;" to='/github'><li class="nav-list-item">Github</li></router-link>
        <router-link style="text-decoration : none; color: inherit;" to='/github'><li class="nav-list-item">Github</li></router-link>
      </ul>
    </div>
  </section>
</template>
<script>
export default {};
</script>

<style lang="sass" scoped>
.nav
    position: fixed
    left: 0
    top: 0
    bottom: 0
    background: #333
    display: flex
    flex-direction: column
    align-items: center
    width: 20vw
    .nav-logo
        margin: 100px auto
    .nav-menu
        color: white
.nav-menu-list
    list-style: none
    padding: 0
    .nav-list-item
        background: #122
        padding: 10px 20px
        text-align: center
        margin: 10px auto
        cursor: pointer
        &:hover
            width: 100%
</style>