<template>
	<view class="box">
		<view class="">
			数据绑定的学习
			{{message}}
		</view>
		<view class="">
			{{1+'你好中国'+'大好'}}
		</view>
		<view class="box">
			{{flag?'我是假的':'我是真的'}}
		</view>
	</view>
</template>

<script>
	export default{
		 data(){
			 return{
				 message:'hello',
				 flag:true,
			 }
		 }
	}
</script>

<style>
</style>
