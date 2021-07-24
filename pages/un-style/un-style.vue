<template>
	
	<!-- rpx -->
	<view class="">
		<view class="box">
			style learn
			
		</view>
		<view class="box1">
			测试文字
			<text class="">ooooo</text>
		</view>
		
		<!-- font的引入 -->
		<view class="iconfont #icon-bianji">
			
		</view>
	</view>
</template>

<script>
</script>
<!-- 如何使用scss 与 less -->
<style lang="scss">
	@import url("./a.css");
	
	.box1{
			width:750rpx;
			height:750rpx;
			background:$global-color;
			font-size: 40rpx;
			text{
				color:pink
			}
		}

</style>
<!-- 不能使用* -->
