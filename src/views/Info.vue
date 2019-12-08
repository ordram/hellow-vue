<template>
  <div class="info">
    <h1>This is an info page</h1>
    <button type="button" @click="add()">添加</button>
  </div>
</template>

<script>
	import store from "@/store/index.js"
	export default {
		name: 'info',
		store,
		methods: {
			add(){
				console.log('add click');
				debugger
				store.commit('arceater');
			}
		}
	}
</script>

<style>
	.info{color: red;}
</style>
