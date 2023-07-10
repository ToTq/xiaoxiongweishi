<template>
	<view class="">
		<view class="header">
			<view class="header_beijing"></view>
			<view class="zhaopian">
				<image class="zhaopian_1" src="../../static/toux.png"></image>
			</view>
		</view>
		<view class="body">
			<view class="body_input">
				<text class="nicheng_text">昵称</text>
				<input class="nicheng" placeholder="小熊宠" placeholder-style="color:#CFCFCF"/>
			</view>
			<view class="body_input">
				<text class="nicheng_text">类型</text>
				<button class="nicheng_button">喵星人</button>
				<button class="nicheng_button">汪星人</button>
			</view>
			<view class="body_input">
				<text class="nicheng_text">性别</text>
				<button class="nicheng_button" >王子</button>
				<button class="nicheng_button" >公主</button>
			</view>
			<view class="body_input">
				<text class="nicheng_text">生日</text>
				<input class="nicheng" placeholder="输入宠物出生日期" placeholder-style="color:#CFCFCF"/>
			</view>
			<view class="body_input">
				<text class="nicheng_text">年龄</text>
				<input class="nicheng" style="width: 200rpx;text-align:center" placeholder="0岁" placeholder-style="color:#CFCFCF"/>
			</view>
		</view>
		<view class="bodybz">
			<text class="nicheng_text_1">备注</text>
		</view>
		<view class="footer">
			<button class="nicheng_button_b">取消</button>
			<button style="background-color: orange;color: white;" class="nicheng_button_b">保存</button>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {
			
		}
	}
</script>

<style>
	page {
		background: #F5F5F5;
	}
	.body {
		position: absolute;
		z-index: 2;
		flex-wrap: nowrap;
		background: white;
		width: 95%;
		margin-left: 20rpx;
		height: 660rpx;
		border-radius: 10px;
		margin-top: -95rpx;
	}
	.bodybz{
		position: absolute;
		z-index: 2;
		display: flex;
		flex-wrap: nowrap;
		background: white;
		width: 95%;
		margin-left: 20rpx;
		height: 120rpx;
		border-radius: 10px;
		margin-top: 590rpx;
	}
	.nicheng{
		height: 43rpx;
		width: 71%;
		margin-top: 40rpx;
		padding:10px 15px;
		border-radius:25px;
		background-color: #F5F5F5;
		margin-left: 20rpx;
	}
	.body_input{
		display: flex;
	}
	.nicheng_text{
		padding-left: 20rpx;
		padding-right: 10rpx;
		padding-top: 21rpx;
		margin-top: 40rpx;
	}
	.nicheng_text_1{
		padding-left: 20rpx;
		padding-right: 10rpx;
		padding-top: 21rpx;
		margin-top: 20rpx;
	}
	.nicheng_button{
		border-radius: 0;
		margin-top: 40rpx;
		border-radius:25px;
		height: 83rpx;
		font-size: 28rpx;
		width: 35%;
		padding-top: 7rpx;
		background-color: #F5F5F5;
	}
	.footer{
		border-radius: 0;
		position: fixed;
		bottom: 0;
		display: flex;
		padding-bottom: 35rpx;
	}
	.nicheng_button_b{
		background-color: #F5F5F5;
		border: 2px solid orange;
		color: orange;
		margin-left: 50rpx;
		height: 95rpx;
		font-size: 28rpx;
		width: 304rpx;
		border-radius:25px;
		margin-top: 40rpx;
		padding-top: 10rpx;
	}
	.nicheng_button_b:active{
		background-color: orange;
		color: white;
	}
	.nicheng_button_b::after{
		border: none;
	}
	.nicheng_button::after{
		border: none;
	}
	.nicheng_button_b:focus{
		background-color: orange;
	}
	.nicheng_button:active{
		background-color: orange;
	}
	.zhaopian{
		text-align:center;
		position: relative;
		top: -56px;
	}
	.zhaopian_1{
		border-radius:50%;
		width: 180rpx;
		height: 180rpx;
	}
	.header_beijing{
		width: 3000rpx;
		height: 3000rpx;
		margin-top: -2850rpx;
		margin-left: -1129rpx;
		background-color: orange;
		border-radius:50%;
	}
	
</style>