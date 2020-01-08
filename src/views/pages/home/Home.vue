<template>
	<div>
		<!-- 轮播图 -->
		<MainCarouselview></MainCarouselview>
		<!-- 其他内容 -->
		<SchoolProfile></SchoolProfile>
	</div>
</template>

<script>
	import MainCarousel from "../../../components/MainCarousel.vue"
	import MainCarouselview from "../../../components/MainCarouselview.vue"
	import SchoolProfile from "./SchoolProfile.vue"
	import SchoolProfileIview from "./SchoolProfileIview.vue"
	
	export default {
		components: {
			MainCarousel,
			MainCarouselview,
			SchoolProfile,
			SchoolProfileIview
		}
	}
</script>

<style>
</style>
