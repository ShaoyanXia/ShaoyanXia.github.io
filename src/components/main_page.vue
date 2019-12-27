<template>
	<div>
		<p class="title">{{msg}}</p>
	</div>
</template>

<script>
	export default {
	  name: 'mainpage',
	  props: {
	    msg: String
	  }
	}
</script>

<style>
	.title{
		font-size: larger;
	}
</style>
