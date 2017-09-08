<template>
	<div class="alert">
		这里是弹出信息
	</div>
</template>

<script>
	export default{
		name:"alert"
	}
</script>

<style>
	.alert{
		width: 20%;
		height: 120px;
		border:1px solid red;
		background: red;
		position: fixed;
		border-radius: 5px;
		box-shadow:#ccc -1px -1px 2px 1px;
		top: 100px;
		left: 40%;
		z-index: 9999;
	}
</style>