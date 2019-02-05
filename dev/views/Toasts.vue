<template>
    <div>
        <h1> Toast Component </h1>
        <br/>
        <FishTankToast></FishTankToast>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'
import {FishTankToast } from '@/index'

export default Vue.extend({
  components:{
    FishTankToast
  },
  data(){
    return {
      
    }
  }
  
})
</script>