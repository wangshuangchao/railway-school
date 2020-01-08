<template>
	<div id="main-content">
		<!-- 导航 -->
		<MainNav></MainNav>
		<!-- 主要内容,跟导航有关系 -->
		<router-view></router-view>
		<!-- 底部,跟导航没关系 -->
		<MainButtom></MainButtom>
	</div>
</template>

<script>
	import MainNav from "../../components/MainNav.vue"
	import MainButtom from "../../components/MainButtom.vue"
	
	export default {
		components: {
			MainNav,
			MainButtom
		}
	}
</script>

<style>
	#main-content {
		/* background-color: aqua; */
		width: 100%;
		position: absolute;
		top: 100px;
		left: 0px;
	}
	
</style>
