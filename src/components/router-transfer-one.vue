<!--  -->
<template>
	<div>
		<h3>{{this.$route.query}}</h3>
		<h1>name：{{this.$route.query.name}}</h1>
		<h1>age：{{this.$route.query.age}}</h1>
		<h1>height：{{this.$route.query.height}}</h1>
	</div>
</template>

<script>
export default {
	data () {
		return {

		}
	},

}

</script>

<style>

</style>