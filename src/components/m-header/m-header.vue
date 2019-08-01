<template>
	<div class="m-header">
		<div class="icon"></div>
		<h1 class="text">Chicken Music</h1>
		<router-link tag="div" class="mine" to="/user">
      <i class="icon-mine"></i>
    </router-link>
	</div>
</template>
<script>
	export default{
	}
</script>
<style scoped lang="less">
.m-header{
	position: relative;
	height:44px;
	text-align: center;
	color:#ffcd32;
	font-size: 0;
	.icon{
		display:inline-block;
		margin-top: 6px;
		margin-right: 9px;
		vertical-align: top;
		width: 30px;
		height:32px;
		background:url(logo@2x.png) no-repeat;
		background-size:30px 32px;
	}
	.text{
		display:inline-block;
		vertical-align:top;
		line-height:44px;
		font-size: 18px;
	}
	.mine{
		position:absolute;
		top:0;
		right: 0;
		.icon-mine{
			font-size: 20px;
			padding:12px;
			display:block;
			color:#ffcd32;
		}
	}
}
</style>
