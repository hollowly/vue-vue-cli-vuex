<!--  -->
<template>
	<div>
		<h2>{{name}}</h2>
		<h2>list：</h2>
		<ul>
			<li v-for='item in lis' :key="item">{{item}}</li>
		</ul>
		<h2>Counter：</h2>
		Current count：{{num}} <br>
		<button @click='add()'>+</button>
		<button @click='sub()'>-</button>
	</div>
</template>

<script>
export default {
	data () {
		return {
			name: 'hello Vue！',
			lis: ['vue','hello','world','hollow'],
			num: 0,
		}
	},
	methods: {
		add() {
			this.num++;
		},
		sub() {
			this.num--;
		}
	},

}

</script>

<style>

</style>