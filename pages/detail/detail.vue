<template>
	<view class="">
		<!-- text -->
		<view class="">
			<text>唱歌跳舞打篮球</text>
		</view>
		<!-- selectable 可以选中功能 -->
		<view class="">
			<text selectable>唱歌跳舞打篮球</text>
		</view>
		<!-- selectable 可以选中功能 空格 -->
		<view class="">
			<text selectable space="ensp">唱歌 跳舞打篮球</text>
		</view>
		<!-- selectable 可以选中功能 字符空格-->
		<view class="">
			<text selectable space="emsp">唱歌 跳舞打篮球</text>
		</view>
		
	
		<!-- class -->
		<view class="box2" hover-class="box2-active">
			<view 
			class="box" 
			hover-class="box-active" 
			hover-stop-propagation
			:hover-start-time="2000"
			:hover-stay-time="2000"
			>
				i am a programmer
			</view>
			
		</view>
		<!-- button 按钮属性 -->
		<view class="">
			<button type="mini">button</button>
			<button type="primary">button</button>
			<button type="primary" plain>button</button>
			<button type="primary" disabled>button</button>
			<button type="mini">button</button>
			<button loading></button>
		</view>
		<!-- image图片 -->
		<!-- mode -->
		<!-- aspectFill 适应宽-->
		<!-- aspectFit 适应高-->
		<view class="">
			<image 
			src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fww1.sinaimg.cn%2Fmw690%2Fac02e02egy1gsi8fye017j20j60pkmzc.jpg&refer=http%3A%2F%2Fwww.sina.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1629193312&t=22bb2d0ab1dd4c101ad24e60b195d4c0" 
			>
			</image>
			<image
			src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fww1.sinaimg.cn%2Fmw690%2Fac02e02egy1gsi8fye017j20j60pkmzc.jpg&refer=http%3A%2F%2Fwww.sina.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1629193312&t=22bb2d0ab1dd4c101ad24e60b195d4c0" 
			mode="aspectFill">
			</image>
			<image
			src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fww1.sinaimg.cn%2Fmw690%2Fac02e02egy1gsi8fye017j20j60pkmzc.jpg&refer=http%3A%2F%2Fwww.sina.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1629193312&t=22bb2d0ab1dd4c101ad24e60b195d4c0" 
			mode="aspectFit">
			</image>
		</view>
		<!-- scss与字体图标 -->
		<view class="">
			
		</view>
		
	</view>
</template>

<script>
</script>

<style>
.box{
	width: 100px;
	height: 100px;
	background: green;
}	
.box2{
	width:200px;
	height:200px;
	background: blue;
}
.box-active{
	background: red;
}
.box2-active{
	background: pink;
}
</style>
