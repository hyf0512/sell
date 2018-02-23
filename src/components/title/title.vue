<template>
	<div class="title">
		<div class="line"></div>
		<div class="text">{{massage}}</div>
		<div class="line"></div>
	</div>
</template>

<script type="text/ecmascript-6">
	export default {
		props: {
			massage: {
				type: String
			}
		}
	}
</script>

<style lang="stylus" rel="stylesheet/stylus">
</style>
