<template>
	<view class="FirstNav Position_Fixed">
		<view class="iconfont icon-sousuo icon"></view>
		<view class="middle">
			<view class="text">首页</view>
			<view class="text">同城</view>
		</view>
	</view>
</template>

<script>
	export default {
		name:"first-nav",
		data() {
			return {
				
			};
		}
	}
</script>

<style>
.FirstNav {
	left: 0px;
	top: 25px;
	height: 35px;
	line-height: 35px;
	width: 100%;
	color: white;
	background: #000000;
}
.icon {
	position: absolute;
	left: 0;
	top: 0;
	width: 20%;
	text-align: center;
	font-size: 20px;
}
.middle {
	text-align: center;
}
.text{
	display: inline;
	color: white;
	margin: 0px 10px;
	font-family:"黑体";
}
</style>
