<!--  -->
<template>
	<div>
		<router-link to='/route-nesting/route-nesting-one' tag='button'>第一页</router-link>
		<router-link to='/route-nesting/route-nesting-two' tag='button'>第二页</router-link>
		<router-view></router-view>
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