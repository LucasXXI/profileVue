<template>
  <img class="profile_lucas" alt="profile_lucas" src="./assets/lucas.svg">
  <Profile msg="Lucas Miranda Leal"/>
</template>

<script>
import Profile from './components/profile.vue'

export default {
  name: 'App',
  components: {
    Profile
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,600;1,500&display=swap');;

body{
  background-color:#34495E;
}

@media(max-width: 1000px){
    img{
      width: 65%;
      margin-top: 40px;
    }
}

#app {
  font-family: Montserrat, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #FFFF;
  margin-top: 60px;
}

</style>
