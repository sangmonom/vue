<template>
	<div>
		<h1>{{title}}</h1>
		<p>{{msg}}</p>
		<p>This is testing for child components.</p>
	</div>
</template>

<script type="text/javascript">
	export default{
		props:{
		msg:String//null//Number
		},
		data (){
			return {
				title: 'Testing Vue'
			}
		}
	}
</script>

<style type="text/css">
	
</style>