<template>
	<dvi>
		<div style="height: 276px;background-color: #333333;">
			<div style="width: 1200px;height: 276px;margin: 0 auto;display: flex;">
				<div class="buttomitem1">
					<div style="width: 90px;height: 25px;font-size: 20px;font-weight: bold;color: #FFF;margin-top: 30px;">
						<p>LOGO</p>
					</div>
					<ul style="list-style-type:none;margin-top: 30px;font-size: 14px;color: #FFFFFF;line-height: 30px;">
						<li>学院网址：http://www.dftlhk.com</li>
						<li>资讯热线：0311-68092339</li>
						<li>公司地址：石家庄桥西区三简路16号</li>
					</ul>
				</div>
				<div class="buttomitem2">
					<div style="margin: 0 auto;width: 67px;margin-top: 30px;">
						<ul style="list-style-type:none;font-size: 16px;color: #FFFFFF;line-height: 30px;cursor:pointer">
							<li @click="buttomTo1">首页</li>
							<li @click="buttomTo2">学校概况</li>
							<li @click="buttomTo3">招生就业</li>
							<li @click="buttomTo4">学员风采</li>
							<li @click="buttomTo5">新闻公告</li>
							<li @click="buttomTo6">联系我们</li>
						</ul>
					</div>
				</div>
				<div class="buttomitem3">
					<div style="width: 130px; float: right;margin-top: 30px;">
						<img src="../assets/images/buttom/15.png" alt="" style="width: 130px;">
					</div>
					<div style="width: 130px; float: right;margin-top: 180px;margin-right: -115px;">
						<p style="font-size: 12px;color: #FFFFFF;">
							扫一扫关注微信公众号
						</p>
					</div>
				</div>
			</div>
		</div>
		<div style="height: 99px; text-align: center;font-size: 14px;">
			<p style="margin-top: 30px;color: #333333;">
				<span>冀ICP备17018905号-4</span><br /><br />
				<span>———— Copyright © 2011-2019 航空公司 版权所有 ————</span>
			</p>
			<!-- <p style="height: 50px;line-height: 50px;">冀ICP备17018905号-4</p>
			<p style="height: 49px;line-height: 49px;">———— Copyright © 2011-2019 航空公司 版权所有 ————</p> -->
		</div>
	</dvi>
</template>

<script>
	export default {
		methods: {
			buttomTo1() {
				this.$store.commit('home')
				this.$router.replace("/home")
			},
			buttomTo2() {
				this.$store.commit('survey')
				this.$router.replace("/schIntroduction")
			},
			buttomTo3() {
				this.$store.commit('students')
				this.$router.replace("/studentBrochure")
			},
			buttomTo4() {
				this.$store.commit('demeanour')
				this.$router.replace("/academyStyle")
			},
			buttomTo5() {
				this.$store.commit('news')
				this.$router.replace("/newsBulletin")
			},
			buttomTo6() {
				this.$store.commit('contact')
				this.$router.replace("/ContactUs")
			}
		}
	}
</script>

<style>
	.buttomitem1 {
		/* width: 100px; */
		height: 276px;
		/* background-color: #008000; */
		flex: 1;
	}
	.buttomitem2 {
		/* width: 100px; */
		height: 276px;
		/* background-color: brown; */
		flex: 1;
	}
	.buttomitem3 {
		/* width: 100px; */
		text-align: right;
		height: 276px;
		/* background-color: #008000; */
		flex: 1;
	}
</style>
