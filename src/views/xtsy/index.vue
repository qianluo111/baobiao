<template>
  
  
    <div class="con_right">
			<div class="con_con">
				<div class="d3">
					天猫超市TMALL.MART
				</div>
				<div class="d4">
					<img src="@/assets/b2.png"/>
				</div>
				<div class="d5">
					<div class="d10">
						<p class="d6">
							<span id="d7">今日疯抢</span>
							<span id="d8">量贩装</span>
						</p>
						<p class="d9"><img src="@/assets/b3.png"/></p>
					</div>
				</div>
				<div class="e1" style="margin-left: 10px;margin-top: 60px;">
					<p id="e2"><img src="@/assets/b4.png"/></p>
					<p id="e3" style="margin-top: 10px;">陈克明面条老妈厨房</p>
					<p id="e3">劲道挂面900g*3麦香</p>
					<p id="e4">¥25.9</p>
				</div>
       
			</div>
		</div>

</template>
<script>
export default {
  name: "Home",
  components: {
  
  },
 
 
};
</script>
<style lang="scss">
.con_right{
	width: 999px;
  height: 549px;
  border-left: 1px solid gray;
}
.con_con{
	 width: 100%;
  height: 498px;
}
.d3{
	width: 210px;
	height: 25px;
	background-color: rgb(0,178,98);
	line-height: 25px;
	text-align: center;
	color: white;
	font-size: 18px;
	float: left;
}

.d4{
	width: 237px;
	height: 619px;
	float: left;
	margin-top: 25px;
	margin-left: -224px;
}
.d4>img{
  width: 210px;
  height: 524px;
}
.d5{
	width: 487px;
	height: 300px;
	background-color: rgb(254,254,254);
	float: left;
	margin-left: 10px;
	margin-top: 60px;
}
.d10{
	width: 361px;
	height: 283px;
	float: left;
	// margin-top: 10px;
	margin-left: 13px;
	background-color: white;
}
.d6{
	width: 461px;
	height: 57px;
	float: left;
}
#d7{
	width: 230px;
	height: 57px;
	float: left;
	background-color: rgb(0,178,98);
	color: white;
	font-size: 17px;
	text-align: center;
	line-height: 57px;
}
#d8{
	width: 230px;
	height: 57px;
	float: right;
	background-color: rgb(241,241,241);
	color: black;
	font-size: 17px;
	text-align: center;
	line-height: 57px;
}
.d9{
	width:461px;
    height: 121px;
    float: left;
}
.e1{
	width: 238px;
	height: 300px;
	float: left;
	background-color: white;
}
#e2{
	width: 187px;
	height: 185px;
	float: left;
	margin-top: 20px;
	margin-left: 24px;
}
#e3{
	width: 145px;
	height: 20px;
	float: left;
	color: black;
	line-height: 20px;
	text-align: center;
	margin-left: 40px;
}
#e4{
	width: 55px;
	height: 20px;
	float: left;
	color: red;
	margin-left: 90px;
	margin-top: 10px;
	font-size: 14px;
	line-height: 20px;
}
</style>
