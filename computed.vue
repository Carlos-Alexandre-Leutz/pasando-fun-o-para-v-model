<template>
  <div>
   <input
   type="checkbox"
   v-model="nomeDocomputed"
    />
  </div>

</template>
<script>
  export default {
   computed:{
        testeInput(){
            
            return true;
        }
    }
  }

</script>
