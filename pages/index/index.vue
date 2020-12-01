<template>
	<view>
		<template v-for="(item,index) in list">
			<view>{{item.create_time}}</view>
			<view class="">
				
			</view>
		</template>
	</view>
</template>

<script>
	data () {
		return {
			list: [], // 消息列表
			page: 1,
			
		}
	}
</script>

<style>
	
	
</style>
