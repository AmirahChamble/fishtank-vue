<template>

<div 
  style="width : 400px;  
 
  ">

  <ContentLoader
		:height="92"
		:width="400"
		:speed="2"
		primaryColor="#f3f3f3"
		secondaryColor="#ecebeb"
	>
		<rect x="0" y="12" rx="4" ry="0" width="191" height="12" /> 
		<rect x="0" y="40" rx="5" ry="0" width="400" height="16" /> 
		<rect x="270" y="12" rx="4" ry="0" width="132" height="12" /> 
		<rect x="0" y="64" rx="5" ry="0" width="364" height="16" />
    <rect x="0" y="91" rx="5" ry="0" width="400" height="1" />
	</ContentLoader>
  <ContentLoader
		:height="92"
		:width="400"
		:speed="2"
		primaryColor="#f3f3f3"
		secondaryColor="#ecebeb"
	>
		<rect x="0" y="12" rx="4" ry="0" width="191" height="12" /> 
		<rect x="0" y="40" rx="5" ry="0" width="400" height="16" /> 
		<rect x="270" y="12" rx="4" ry="0" width="132" height="12" /> 
		<rect x="0" y="64" rx="5" ry="0" width="364" height="16" />
    <rect x="0" y="91" rx="5" ry="0" width="400" height="1" />
	</ContentLoader>

</div>
</template>
<script lang="ts">
import { ContentLoader } from "vue-content-loader"
import Vue from 'vue'

export default Vue.extend({
  components:{
    ContentLoader
  },
  
})
</script>
