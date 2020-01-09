<template>
	<div>
		<div><img src="../../../assets/images/enrollmentEmployment/0.png" alt="" style="width: 100%;"></div>
		<div style="width: 1200px;margin: 0 auto;display: flex;margin-top: 30px;margin-bottom: 30px;">
			<div style="width: 300px;height: 260px;">
				<div style="height: 160px;background-color: #1A49DB;"></div>
				<div 
				style="height: 50px;cursor: pointer;line-height: 50px;text-align: center;color: #1A49DB;font-size: 16px;font-weight: bold;"
				:class="{activeOnStu: activeOnStu}" @click="activeOnStuM">
					招生简章
				</div>
				<div 
				style="height: 50px;cursor: pointer;line-height: 50px;text-align: center;color: #1A49DB;font-size: 16px;font-weight: bold;"
				:class="{activeOnEmp: activeOnEmp}" @click="activeOnEmpM">
					就业保障
				</div>
			</div>
			<div style="width: 898px;border-left: solid 2px #E6E6E6;">
				<router-view></router-view>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				activeOnStu: false,
				activeOnEmp: true
			}
		},
		methods: {
			activeOnStuM() {
				this.activeOnStu = true
				this.activeOnEmp = false
				this.$router.replace("/studentBrochure/studentBrochureChild")
			},
			activeOnEmpM() {
				this.activeOnStu = false
				this.activeOnEmp = true
				this.$router.replace("/studentBrochure/employmentSecurityChild")
			}
		}
	}
</script>

<style>
	/* .activeOnStu,.activeOnEmp {
		background-color: #d2dcf8;
	} */
</style>
