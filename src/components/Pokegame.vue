<template>
  <div class="hello">
    <ul>
      <li v-for="pokemon in Pokedex" v-bind:key="pokemon.id">
        {{pokemon.name.english}}
      </li>
    </ul>
  </div>
</template>

<script>

import Pokedex from '../assets/data/pokedex.json'

export default {
  name: 'Pokegame',
  props: {
    msg: String
  },

  data() {
    return {
      Pokedex
    };
  },
  methods: {
    imagePkmn: function(){
      pokedex.forEach( pokemon{
        
      })
    };
},

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
