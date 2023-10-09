<template>
	<view class="content">
		<u-button @click="show = true">uViewBUTTON</u-button>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onLoad() {
			console.log('uView version:', uni.$u.config.v)
		},
		methods: {
			
		}
	}
</script>

<style lang="scss">
	
</style>
