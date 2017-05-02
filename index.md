<html lang="en">
<head>
	<meta charset="UTF-8">
	<link rel="stylesheet" type="text/css" href="css/index.css" />
	<style type="text/css">
	/*导航css开始*/
		*{
			margin: 0;
			padding: 0;
		}
		body{	
		}
		.navcolor{
			background-color: #191D3A;
		}
		.clear{
			clear: both;
		}
		.top{
			height: 58px;
			width: 1000px;
			margin: auto;
			padding-bottom: 3px;
		}
		.top .logo,.top .jrwm{
			float: left;
		}
		.top ul li{
			float: left;
			height:58px;
			line-height: 58px;
			text-align: center;
			width: 100px;
			font-size: 16px;
			color: #fff;
		}
		.jrwm{
			float: left;
			padding-top:12px;
			padding-left:70px;
		}

		.top .nav ul li{
			list-style-type: none;
			border-left: 1px solid #232745;
		}
		/*伪类选择器*/
		ul li a:link,a:visited{
			color: #71838b;
			text-decoration: none;
		}
		ul li a:hover,a:active{
			background-color: #252947;
		}

		a{	
			/*a标签的高度跟父元素一样*/
			display: block;
		}
		/*导航css结束*/

		/*******************banner开始***********************/
			.banner{
				width: 1920px;
				height: 465px;
				margin: 0px auto;
			}
				/*******************banner结束***********************/
			}
		/*视频栏目开始*/
		.video{
			width: 1000px;
			margin:0px auto;
		}

		.videowh{
			width: 218px;
			height: 130px;
			float: left;
			margin: 50px 15px;
		}
		.video1{
			background-image: url(./images/1.jpg);
		}
		.video2{
			background-image: url(./images/2.jpg);
		}
		.video3{
			background-image: url(./images/3.jpg);
		}
		.video4{
			background-image: url(./images/4.jpg);
		}
		

		/*视频栏目结束*/

		/*************新闻开始****************/
		.down{
			width: 1000px;
			margin: 0px auto;
			padding-top:50px;
			padding-bottom: 50px;
		}
		.news{
			width: 500px;
			float: left;
		}
		.new {
			width: 500px;
			padding: 50px 50px 0px 50px;
		}

		.new ul li{
			height: 50px;
			line-height: 50px;
			border-bottom: 1px solid #DBE1E7;
			color: #444866;
		}
		.newstitle{
			width: 500px;
			height: 310px;
			background-image: url(images/bynewsbg.jpg);
		}
		.more{
			width: 67px;
			height: 28px;
			background-image: url(images/more.png);
			float: left;
			margin-top: 37px;
			margin-left: 217px;
			background-repeat: no-repeat;
		}

		/*************新闻结束****************/
		/*************hr开始****************/
		.hr{
			width: 500px;
			height: 310px;
			float:left;
			background-image: url(./images/zczp.jpg);
		}
		.zczp{
			background-image: url(images/zczp.png);
			width:119px; 
			height:51px;
			margin-top: 44px;
			margin-left:80px;
			float: left;
		}
		.more_2{
			background-image: url(images/more2.png);
			width: 66px;
			height: 28px;
			float: left;
			margin-top: 40px;
			margin-left: 25px;

		}
		.down ul li{
			list-style-type: none;
		}
		.zhiwei{
			color:#fff;
			margin-left: 21px;
		}

		.zhiwei ul li{
			height: 48px;
			line-height: 48px;
			border-bottom: 1px solid #6FDEA3;
			font-size: 14px;
			 background-position: center; 
		}
		/*************hr结束****************/

		/*******************foot开始**********************/


		.foot{

			height:90px;
			width: 100%;
			background-color: #191D3A;
		}
		.yewei{
			width: 1000px;
			margin:0px auto;
			height: 92px;
			line-height: 92px;
			font-size: 14px;
			color:#6C6E7E;
		}
		.copy{
			float: right;
		}
		.wangjing{
			background-image: url(./images/govIcon.gif);
			border-image-repeat: no-repeat;
			float: right;
			width: 40px;
			height: 52px;
			padding:10px; 


		}
		/*******************foot结束**********************/

	</style>
	<title>Document</title>
</head>
<body>
	<!-- 导航开始 -->
	<div class='navcolor'>
		<div class="top">
			<div class="logo">
				<img src="images/logo.png">
			</div>
			<div class="nav">
				<ul>
					<li><a href="#">首页</a></li>
					<li><a href="#">博雅游戏</a></li>
					<li><a href="#">博雅新闻</a></li>
					<li><a href="#">关于我们</a></li>
					<li><a href="#">客服中心</a></li>
					<li><a href="#">投资者关系</a></li>
				</ul>
			</div>
			<div class="jrwm">
				<img src="images/jrwm.png">
			</div>
		</div>
	</div>	
	<!-- 导航结束 -->
	<!-- banner ***************居中******************开始-->
	<div>
		<img src="images/banner1.jpg" alt="">
	</div>
	<!-- banner结束 -->
	<!-- 宣传开始 -->
	<div class="video">
		<div class="video1 videowh"></div>
		<div class="video2 videowh"></div>
		<div class="video3 videowh"></div>
		<div class="video4 videowh"></div>
		<div class="clear"></div>
	</div>
	<!-- 宣传结束 -->
	<!-- 新闻开始 -->
	<div class="down">
				<div class="news">
						<div class="newstitle">
							<div class='more'></div>
							<div class="clear"></div>
							<div class="new">
							<ul>
								<li>2015博雅国际扑克大赛(BPT)在澳门落幕</li>
								<li>2015 BPT博雅国际扑克大赛重磅来袭</li>
								<li>博雅互动与阿里游戏联手启动"淘宝杯首届电视棋牌大赛"</li>
								<li>湖南省省长杜家毫一行参观博雅互动</li>
							</ul>
						</div>
						</div>
						
				</div>

			<div class="hr">
				<div class='zczp'></div>
				<div class='more_2'></div>
				<div class="clear"></div>
				<div class='zhiwei'>
				<h4>专场招聘岗位</h4>
					<ul>
						<li>PHP开发工程师</li>
						<li>C++开发工程师</li>
						<li>WEB前端开发工程师</li>
						<li>W大数据开发工程师</li>
					</ul>
				</div>
			</div>
			<div class="clear"></div>
	</div>
	<!-- 新闻结束 -->
	<!--foot开始-->
		<div class="foot">
			<div class="yewei"> 
				<span class="wzdt">
					网站地图 | 免责声明
					
				</span>
				<div class="wangjing"></div>
				<span class="copy">
					copyroght &copy; 2004-2014博雅互动(Boyya Interactive) 粤ICP备05062536号 增值电信业务经营许可证：粤B2-20112513
				</span>
			</div>
		</div>

	<!--foot结束-->
	
</body>
</html>
