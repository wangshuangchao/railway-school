<template>
	<div id="main-title">
		<div id="logo" style="margin-top: 15px;">
			<img src="../assets/images/title/0.png" alt=""
			style="width: 600px;">
		</div>
		<div id="cellphone">
			<span style="color: #1A49DB;font-size: 16px;">咨询热线</span>
			<span style="color: #1A49DB;font-size: 30px;">0311-68092339</span>
		</div>
	</div>
</template>

<script>
	export default {
		
	}
</script>

<style>
	#main-title {
		z-index:999;
		height: 100px;
		line-height: 100px;
		width: 100%;
		background-color: #FFFFFF;
		position: fixed;
		top: 0px;
		left: 0px;
	}
	#logo {
		/* width: 100px; */
		height: 30px;
		line-height: 30px;
		/* background-color: #0000FF; */
		color: red;
		display: inline-block;
		margin-left: 150px;
	}
	#cellphone {
		/* width: 100px; */
		height: 30px;
		line-height: 30px;
		/* background-color: #0000FF; */
		color: red;
		display: inline-block;
		float: right;
		margin-right: 100px;
		margin-top: 30px;
	}
</style>


