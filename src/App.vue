<template>
  <router-view/>
</template>
<script>
export default{
	beforeMount(){
		this.$store.commit('sessionUser')
	}
}
</script>