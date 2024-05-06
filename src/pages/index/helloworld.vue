<template>
	<view class="content">
		
		<view>
			<text class="title">{{title}}</text>
		</view>

		<view>
			<text>参与GitHbutler开源项目不？三天6K星的</text>
			<text>变态好用的GitHbutler</text>
			<text>学vue吧，比css</text>
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
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin: 200rpx auto 50rpx auto;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
