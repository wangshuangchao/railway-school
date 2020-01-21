<template>
	<div id="school-profile">
		<h2 >学校概况</h2>
		<hr />
		<div class="horizontal-row">
			<div><img src="../../../assets/images/home/5.png" alt=""></div>
			<div>
				<h1>一、学校简介：</h1>
				<div style="height: 250px;margin-top: 20px;text-indent:2em;color: #666666;font-size: 16px;">
					<p>
						交通业是国家的命脉，是国家发展的重要保证。根据十八大精神，中国建设“八横八纵”交通枢纽网，推动交通、经济发展，给同学们带来大量的就业机遇和岗位。中国一些一线二线城市为了赶上时代步伐、推进城市发展，建设地铁、高铁等现代交通方式。交通类专业的前景是灿烂辉煌的，交通类工作者是国家的必要也是必须人才。我校以培养国家实用型人才为宗旨，为实现中国伟大复兴为己任。
					</p>
					<br />
					<p>
						石家庄市东方铁路航空中等专业学校建于2010年，是经石家庄教育局批准，具有独立颁发中等职业毕业证资格的全日制职业中专学校。学校以学历教育、技能教育综合型为特色，为国家培养具有“一技之长”“一专多能”的高学历技能人才。
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
				<!-- <ul style="margin-left: 25px;color: #333333;line-height: 35px;margin-top: 15px;font-size: 16px;">
					<li>航空学院优秀学院赴海南航空实习<span style="color: #666666;margin-left: 220px;">2019-12-09</span></li>
					<li>航空学院优秀学院赴海南航空实习<span style="color: #666666;margin-left: 220px;">2019-12-09</span></li>
					<li>航空学院优秀学院赴海南航空实习<span style="color: #666666;margin-left: 220px;">2019-12-09</span></li>
					<li>航空学院优秀学院赴海南航空实习<span style="color: #666666;margin-left: 220px;">2019-12-09</span></li>
					<li>航空学院优秀学院赴海南航空实习<span style="color: #666666;margin-left: 220px;">2019-12-09</span></li>
					<li>航空学院优秀学院赴海南航空实习<span style="color: #666666;margin-left: 220px;">2019-12-09</span></li>
				</ul> -->
			</div>
			<div>
				<div style="font-size: 24px;color: #333333;font-weight: bold;margin-bottom: 15px;">
					<span style="border-right:4px solid #EE9900;padding-right:10px;margin-right: 5px;" />
					就业保障
					<span style="color: #EE9900; margin-left: 400px;cursor:pointer;font-size: 16px;font-weight: bold;" @click="toEmploymentSecurity">更多+</span>
				</div>
				<hr style="width: 560px;color: #CCCCCC;border: solid 1px;"/>
				<!-- 
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
			 -->
			</div>
		</div>
		
		<div style="margin-top: 30px;">
			<div style="font-size: 24px;color: #333333;font-weight: bold;margin-bottom: 15px;">
				<span style="border-right:4px solid #EE9900;margin-right: 5px;" />
				<span style="margin-right: 145px;">学校新闻</span>
				<span style="color: #EE9900; margin-left: 850px;cursor:pointer;font-size: 16px;font-weight: bold;" @click="tonewsBulletin">更多+</span>
			</div>
			<!-- 
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
			 -->
		</div>
		
		
		<div style="background-color: #F2FAFE;margin-top: 30px;">
			<h2 >合作单位</h2>
			<hr />
			<!-- <div style="margin-top: 30px; text-align: center;">
				<div class="cooperation"><img src="../../../assets/images/home/cooperation/11.png" alt=""></div>
				<div class="cooperation"><img src="../../../assets/images/home/cooperation/12.png" alt=""></div>
				<div class="cooperation"><img src="../../../assets/images/home/cooperation/13.png" alt=""></div>
				<div class="cooperation"><img src="../../../assets/images/home/cooperation/14.png" alt=""></div>
			</div> -->
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
		margin-bottom: 60px;
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
		margin-top: 50px;
	}

	.horizontal-row>div {
		margin-top: 30px;
		float: left;
		width: 590px;
		height: 300px;
		margin: 0 auto;
		/* color: red; */

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
