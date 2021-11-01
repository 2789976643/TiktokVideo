<template>
	<view class="tab Position_Fixed">
		<view class="tab-box">首页</view>
		<view class="tab-box">关注</view>
		<view class="tab-box">
			<view class="icon-box iconfont icon-jiahao1">
			</view>
		</view>
		<view class="tab-box">消息</view>
		<view class="tab-box">我</view>
	</view>
</template>

<script>
	export default {
		name:"tab",
		data() {
			return {
				
			};
		}
	}
</script>

<style>
.tab{
	width: 100%;
	height: 50px;
	line-height: 50px;
	bottom: 0px;
	display: flex;
	text-align: center;
}	
.tab-box {
	width: 100%;
	background: #000;
	color: white;
}
.icon-box {
	width: 60%;
	height: 25px;
	line-height: 25px;
	margin: 12.5px 20%;
	background: white;
	color: #000000;
	border-radius: 4px;
	font-size: 15px;
}
</style>
