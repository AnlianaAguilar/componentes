<template>
  <div id="app">


  </div>
</template>

<script>


export default {
  name: 'App',
  data(){
    return{
      character:[
        {
          nombre: "Rick Sanchez",
          src:"https://rickandmortyapi.com/api/character/avatar/1.jpeg"
        },
        {
          nombre: "Morty Smith",
          src:"https://rickandmortyapi.com/api/character/avatar/2.jpeg"
        },
        {
          nombre: "Summer Smith",
          src:"https://rickandmortyapi.com/api/character/avatar/3.jpeg"
        },
        {
          nombre: "Beth Smith",
          src:"https://rickandmortyapi.com/api/character/avatar/4.jpeg"
        },
        {
          nombre: "Jerry Smith",
          src:"https://rickandmortyapi.com/api/character/avatar/5.jpeg"
        },
        {
          nombre: "Abadango Cluster Princess",
          src:"https://rickandmortyapi.com/api/character/avatar/6.jpeg"
        },
        {
          nombre: "Abradolf Lincler",
          src:"https://rickandmortyapi.com/api/character/avatar/7.jpeg"
        }
      ]
    }
  },
  components: {
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

body{
  background-image: url(https://rickandmortypod.com/wp-content/uploads/2018/11/cropped-RM_page-header_background1-3.png);
}
</style>
