<template>
	<div id="school-profile">
		<h2 >学校概况</h2>
		<hr />
		<div class="horizontal-row">
			<div><img src="../../../assets/images/home/5.png" alt=""></div>
			<div>
				<div style="height: 250px;margin-top: 20px;text-indent:2em;color: #666666;font-size: 16px;">
					<p>
					学校前身是创建于1934年的国立西北农林专科学校。1999年9月，经国务院批准，由原西北农业大学、西北林学院、中国科学院水利部水土保持研究所、水利部西北水利科学研究所、陕西省农业科学院、陕西省林业科学院、陕西省中国科学院西北植物研究所等7所科教单位合并组建为西北农林科技大学。
					</p>
					<br />
					<p>
						 建校80余年来，学校一代代师生秉承“经国本，解民生，尚科学”的办学理念和“诚朴勇毅”的校训，心怀社稷，情系苍生，承远古农神后稷之志，行当代“教民稼穑”之为，坚持走产学研紧密结......
					</p>
				</div>
				<p style="color: #EE9900; margin-left: 500px;cursor:pointer;font-size: 16px;font-weight: bold;" @click="toSchIntroduction">更多+</p>
			</div>
		</div>
		<div class="horizontal-row">
			<div>
				<div style="font-size: 24px;color: #333333;font-weight: bold;margin-bottom: 15px;">
					<span style="border-right:4px solid #EE9900;padding-right:10px;margin-right: 5px;" />
					学校活动
					<span style="color: #EE9900; margin-left: 400px;cursor:pointer;font-size: 16px;font-weight: bold;" @click="toAcademyStyle">更多+</span>
				</div>
				<hr style="width: 560px;color: #CCCCCC;border: solid 1px;"/>
				<ul style="margin-left: 25px;color: #333333;line-height: 35px;margin-top: 15px;font-size: 16px;">
					<li>航空学院优秀学院赴海南航空实习<span style="color: #666666;margin-left: 220px;">2019-12-09</span></li>
					<li>航空学院优秀学院赴海南航空实习<span style="color: #666666;margin-left: 220px;">2019-12-09</span></li>
					<li>航空学院优秀学院赴海南航空实习<span style="color: #666666;margin-left: 220px;">2019-12-09</span></li>
					<li>航空学院优秀学院赴海南航空实习<span style="color: #666666;margin-left: 220px;">2019-12-09</span></li>
					<li>航空学院优秀学院赴海南航空实习<span style="color: #666666;margin-left: 220px;">2019-12-09</span></li>
					<li>航空学院优秀学院赴海南航空实习<span style="color: #666666;margin-left: 220px;">2019-12-09</span></li>
				</ul>
			</div>
			<div>
				<div style="font-size: 24px;color: #333333;font-weight: bold;margin-bottom: 15px;">
					<span style="border-right:4px solid #EE9900;padding-right:10px;margin-right: 5px;" />
					就业保障
					<span style="color: #EE9900; margin-left: 400px;cursor:pointer;font-size: 16px;font-weight: bold;" @click="toEmploymentSecurity">更多+</span>
				</div>
				<hr style="width: 560px;color: #CCCCCC;border: solid 1px;"/>
				<div>
					<div>
						<img src="../../../assets/images/home/6.png" alt="" style="width: 150px;margin-top: 20px;margin-left: 15px;">
						<div style="float: right;margin-top: 20px;">
							<p style="color: #333333;font-size: 16px;font-weight: bold;">
                                【2019-12-16】王艳艳同学成功进入中国东方航空公司就职
                            </p>
							<p style="margin-top: 20px;margin-left: 20px;color: #999999;font-size: 14px;">
								上海东方航空人力资源和社会保障厅公布了2019年<br />
								山东省博士后创新实践基地名单。文登区推荐报送...
								                            
							</p>
						</div>
					</div>
					<div>
						<img src="../../../assets/images/home/7.png" alt="" style="width: 150px;margin-top: 5px;margin-left: 15px;">
						<div style="float: right;margin-top: 20px;">
							<p style="color: #333333;font-size: 16px;font-weight: bold;">
						        【2019-12-16】王艳艳同学成功进入中国东方航空公司就职
						    </p>
							<p style="margin-top: 20px;margin-left: 20px;color: #999999;font-size: 14px;">
								上海东方航空人力资源和社会保障厅公布了2019年<br />
								山东省博士后创新实践基地名单。文登区推荐报送...
								                            
							</p>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div style="margin-top: 30px;">
			<div style="font-size: 24px;color: #333333;font-weight: bold;margin-bottom: 15px;">
				<span style="border-right:4px solid #EE9900;margin-right: 5px;" />
				<span style="margin-right: 145px;">学校新闻</span>
				<span style="color: #EE9900; margin-left: 850px;cursor:pointer;font-size: 16px;font-weight: bold;" @click="tonewsBulletin">更多+</span>
			</div>
			<div style="margin-top: 30px; display: flex;">
				<div class="shlnews">
					<img src="../../../assets/images/home/8.png" alt="">
					<p style="text-align: start;margin-left: 40px;margin-top: 20px;color: #333333;font-size: 20px;font-weight: bold;">2019年寒假放假通知</p>
					<p style="text-align: start;margin-left: 30px;margin-right: 20px;margin-top: 15px;color: #999999;font-size: 14px;">永保保险 106种重疾+55种轻症保障终身,重疾赔付5次,轻症赔付3次,赔付金额高.永诚保险网站_可保160种疾病,分组多次赔付累计高达216万,可附加300万.</p>
					
				</div>
				<div class="shlnews">
					<img src="../../../assets/images/home/9.png" alt="">
					<p style="text-align: start;margin-left: 40px;margin-top: 20px;color: #333333;font-size: 20px;font-weight: bold;">选择消费型重疾保险，保费更便宜...</p>
					<p style="text-align: start;margin-left: 30px;margin-right: 20px;margin-top: 15px;color: #999999;font-size: 14px;">t保险网站_可保160种疾病,分组多次赔付累计高达216万,可附加300万.</p>
					
				</div>
				<div class="shlnews">
					<img src="../../../assets/images/home/10.png" alt="">
					<p style="text-align: start;margin-left: 40px;margin-top: 20px;color: #333333;font-size: 20px;font-weight: bold;">新学期新起点</p>
					<p style="text-align: start;margin-left: 30px;margin-right: 20px;margin-top: 15px;color: #999999;font-size: 14px;">永保保险 106种重疾+55种轻症保障终身,重疾赔付5次,轻症赔付3次,赔付金额高.永诚保险网站_可保160种疾病,分组多次赔付累计高达216万,可附加300万.</p>
					
				</div>
			</div>
			
		</div>
		<div style="background-color: #F2FAFE;margin-top: 30px;">
			<h2 >合作单位</h2>
			<hr />
			<div style="margin-top: 30px; text-align: center;">
				<div class="cooperation"><img src="../../../assets/images/home/cooperation/11.png" alt=""></div>
				<div class="cooperation"><img src="../../../assets/images/home/cooperation/12.png" alt=""></div>
				<div class="cooperation"><img src="../../../assets/images/home/cooperation/13.png" alt=""></div>
				<div class="cooperation"><img src="../../../assets/images/home/cooperation/14.png" alt=""></div>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		methods: {
			toSchIntroduction() {
				this.$store.commit('survey')
				this.$router.replace("/schIntroduction")
			},
			toAcademyStyle() {
				this.$store.commit('demeanour')
				this.$router.replace("/academyStyle")
			},
			toEmploymentSecurity() {
				this.$store.commit('students')
				this.$router.replace("/employmentSecurity")
			},
			tonewsBulletin() {
				this.$store.commit('news')
				this.$router.replace("/newsBulletin")
			}
			
		}
	}
</script>

<style>
	#school-profile {
		text-align: center;
		margin-top: 30px;
		width: 1200px;
		/* height: 2000px; */
		/* background-color: #000000; */
		margin: 0 auto;
		margin-top: 30px;
	}
	
	#school-profile>div:nth-child(4) {
		background-color: #F2FAFE;
	}

	#school-profile h2 {
		font-size: 34px;
		color: #333333;
	}

	#school-profile hr {
		border: solid 2px;
		width: 60px;
		margin: 0 auto;
		color: #EE9900;
	}

	.horizontal-row {
		text-align: start;
		/* background-color: #EE9900; */
		margin-top: 30px;
	}

	.horizontal-row>div {
		margin-top: 30px;
		float: left;
		width: 590px;
		height: 300px;
		margin: 0 auto;
		color: red;

	}

	.horizontal-row>div:nth-child(1) {
		/* background-color: #0000FF; */
		margin-right: 10px;
	}

	.horizontal-row>div:nth-child(1) img {
		width: 590px;
		height: 300px;
	}

	.horizontal-row>div:nth-child(2) {
		/* background-color: #00FF00; */
		margin-left: 10px;
	}

	.horizontal-row::after {
		content: "";
		clear: left;
		display: block;
	}
	
	.shlnews {
		flex: 1;
	}
	.shlnews img {
		width: 370px;
	}
	
	.cooperation {
		/* flex: 1; */
		display: inline-block;
		width: 240px;
		height: 240px;
		background-color: #FFFFFF;
		margin-bottom: 30px;
		margin: 20px;
	}
	.cooperation  img {
		width: 240px;
		height: 240px;
	}
	
</style>
