<template>
	<div id="firstcomponent">
		<h1>这是标题</h1>
		<a>作者：{{ author }}</a>
	</div>
</template>

<script type="text/javascript">
	export default{
		data(){
			return {
				author:'陈鹏cpdhogjo'
			}
		}
	}
</script>

<style type="text/css">
	#firstcomponent h1{
		font-weight: 900;
		font-family: "微软雅黑";
		color: red;
	}
</style>
