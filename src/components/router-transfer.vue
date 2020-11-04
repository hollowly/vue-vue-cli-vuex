<!--  -->
<template>
	<div>
		<router-link :to="{path:'/router-transfer/router-transfer-one',
		query:{name:'hollow',age:18,height:1.88}}">参数传递1</router-link>
		<button @click='btnClick'>参数传递2</button>

		<router-view></router-view>
	</div>
</template>

<script>
export default {
	data () {
		return {

		}
	},
	methods: {
		btnClick() {
			this.$router.replace(
				{
					path:'/router-transfer/router-transfer-two',
					query:{
						name:'djx',
						age:999,
						height:999.99
					}
				}
			)
		}
	}

}

</script>

<style>

</style>