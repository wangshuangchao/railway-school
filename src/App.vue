<template>
	<div id="app">
		<!-- 标题logo -->
		<MainTitle></MainTitle>
		<!-- 内容 -->
		<MainContent></MainContent>
	</div>
</template>

<script>
	import MainTitle from "components/MainTitle.vue"
	import MainContent from "views/containt/MainContent.vue"

	export default {
		components: {
			MainTitle,
			MainContent
		}
	}
</script>

<style>
</style>
