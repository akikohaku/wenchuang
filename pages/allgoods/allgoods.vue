<template>
	<view>
		<view class="goods">
			<view class="goods-pic">
				<image src="../../static/logo.png" mode="widthFix"></image>
			</view>
			<view class="goods-price">
				￥200,0
			</view>
			<view class="old-price">
				￥100,0
			</view>
			<view class="discription">
				[受注生产]湘南猫弓背特色纸雕灯
			</view>
		</view>
		<view class="goods">
			<view class="goods-pic">
				<image src="../../static/logo.png" mode="widthFix"></image>
			</view>
			<view class="goods-price">
				￥200,0
			</view>
			<view class="old-price">
				￥100,0
			</view>
			<view class="discription">
				[受注生产]湘南猫弓背特色纸雕灯
			</view>
		</view>
		<view class="goods">
			<view class="goods-pic">
				<image src="../../static/logo.png" mode="widthFix"></image>
			</view>
			<view class="goods-price">
				￥200,0
			</view>
			<view class="old-price">
				￥100,0
			</view>
			<view class="discription">
				[受注生产]湘南猫弓背特色纸雕灯
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
	@font-face {
		font-family: 'ZCOOL QingKe HuangYou';
		src: url(../../static/fontsZCOOL.css);
	}
	.goods{
		width: 47%;
		height: 500rpx;
		border: 2rpx solid #00000033;
		border-radius: 15rpx;
		margin-top: 10rpx;
		margin-left: 10rpx;
		display: inline-block;
	}
	.goods-pic{
		margin: 20rpx auto;
		width:80%;
		height: auto;
		text-align: center;	
		
	}
	.goods-pic image{
		height:auto;
		width:100%;
	}
	.goods-price{
		margin-left: 20rpx;
		font-family: 'ZCOOL QingKe HuangYou';
		color: red;
		font-size: 45rpx;
		float: left;
	}
	.old-price{
		font-family: 'ZCOOL QingKe HuangYou';
		color: grey;
		font-size: 25rpx;
		text-decoration:line-through;
		padding-top: 15rpx;
		padding-left: 15rpx;
		margin-bottom: 5rpx;
		height: 30rpx;
		
	}
	.discription{
		margin:0 auto;
		width: 90%;
		float: none;
		font-size: 28rpx;
	}
</style>
