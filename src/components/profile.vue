<template>
  <h1>{{ msg }}</h1>
  <h2>Desenvolvedor</h2>
  <a href="https://github.com/LucasXXI">
    <img
      class="git"
      src="../assets/github_icon.svg"
      onclick="https://github.com/LucasXXI"
    />
  </a>
  <a href="https://linkedin.com/in/lucasleal2001">
    <img class="linkedin" src="../assets/linkedin_icon.svg" />
  </a>
</template>

<script>
export default {
  name: "Profile",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
h1 {
  font-size: 3rem;
}

h2 {
  color: #42b883;
  font-size: 2rem;
  margin-top: -0.5em;
}

.git {
  margin-top: 5%;
  margin-right: 3rem;
}

@media(max-width:1000px){
  h1{
    font-size: 1.5rem;
  }

  h2{
    font-size: 1rem;
  }

  img{
    width: 20%;
  }
}
</style>
