<template>
	<h1 class="green">h2...{{tt}}...title:{{title}}</h1>
</template>

<script>
	export default {
		name: "test",
		props:['title'],
		data(){
			return {
				tt: "this page",
			}
		}
	}
</script>

<style>
	.green{color: #8bff1e;}
</style>
