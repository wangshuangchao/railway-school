<template>
	<div>
		<div><img src="../../../assets/images/newsBulletin/0.png" alt="" style="width: 100%;"></div>
		<div style="width: 1200px;margin: 0 auto;display: flex;color: #FFFFFF;margin-top: 30px;margin-bottom: 30px;font-size: 18px;">
			<div style="flex: 1;text-align: right;margin-right: 20px;">
				<button style="width: 120px;height: 50px;border-radius:8px;border:none;outline:0;cursor: pointer;"
					:class="{btnAction: btnAction1, btnUnAction: btnAction2}"
					@click="btnActionA">
					学校动态
				</button>
			</div>
			<div style="flex: 1;text-align: left;margin-left: 20px;">
				<button style="width: 120px;height: 50px;border-radius:8px;border:none;outline:0;cursor: pointer;"
					:class="{btnAction: btnAction2, btnUnAction: btnAction1}"
					@click="btnActionB">
					学校新闻
				</button>
			</div>
		</div>
		<div style="width: 1200px;margin: 0 auto;margin-bottom: 30px;">
			<router-view></router-view>
		</div>
	</div>
</template>

<script>
	export default {
		data()  {
			return {
				btnAction1: true,
				btnAction2: false
			}
		},
		methods: {
			btnActionA() {
				this.btnAction1 = true
				this.btnAction2 = false
				this.$router.replace('/newsBulletin/schDynamic')
			},
			btnActionB() {
				this.btnAction1 = false
				this.btnAction2 = true
				this.$router.replace('/newsBulletin/schNews')
			}
		}
	}
</script>

<style>
	.btnAction {
		background-color: #1A49DB;
	}
	.btnUnAction {
		background-color: #B3B3B3;
	}
</style>
