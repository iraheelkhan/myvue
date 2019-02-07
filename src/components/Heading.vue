<template>
<div>
	<h1> My Name is {{name}}</h1>
</div>
</template>
<script>
export default{
		name: 'heading',
		props: ['name'],
		data:{
			name:'raheel',
		}
	}
</script>