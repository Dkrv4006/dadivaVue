<template>
  <v-app-bar :elevation="1" color="indigo-darken-4" height="100">
    DADIVA 
    <div>
      
      <router-link to="Acionamento" active-class="active">
        <v-btn class="text-#ffffff bg-indigo-darken-2 ml-10" >
          Acionamento
        </v-btn>
      </router-link>
      <router-link to="/Os" active-class="active">
        <v-btn  class="text-#ffffff bg-indigo-darken-2 ml-5 "> O.s </v-btn>
      </router-link>
  
    
    </div>
  </v-app-bar>
  <v-main>
    <router-view />
  </v-main>
</template>

<script setup>
  //
</script>

<style>
.active{
  filter: brightness(0.8);
}
.b{
  background-color: y ;
}
</style>
