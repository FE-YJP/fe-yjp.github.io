<html>
	<head>
		<meta charset="utf-8" />
		<style type="text/css">
			body,h1{
					margin: 0;
					padding: 0;
					-webkit-box-sizing: border-box;
					-moz-box-sizing: border-box;
					box-sizing: border-box;
					
				}
				body{
					background-color: rgba(0,0,0,.2);
				}
				a{
					text-decoration: none;
					font-family: "microsoft yahei";
					color: rgba(0,0,0,2);
					transition: 500ms;
				}
				#content{
					width: 1000px;
					margin: 0 auto;
					padding: 0;
				}
				
				.box1 ul li a:hover{
					color: white;
				}
				.header,
				.main{
					width:100%;
					margin: 10px auto;
				}
				.header{
					background: rgba(0,0,0,.2);
					height: 50px;
				}
				.main{
					height: 400px;
				}
				.main,
				.box,
				.box1,
				.box2,
				.header{
					text-align: center;
					border-radius:15px ;
				}
				.box{
					width: 60%;
					height: 100%;
					margin:0 auto;
					background-color:rgba(0,0,0,.2);
					/* background-image: url(../img/309738-106.jpg); */
					display: inline-block;
				}
				.box1{
					width: 150px;
					height: 100%;
					background: rgba(0,0,0,.2);
					float: left;
					display: inline-block;
					
				}
				.box2{
					width: 20%;
					height: 100%;
					background: rgba(0,0,0,.2);
					display: inline-block;
					float: right;
					position: relative;
				}
				.box1 ul {
					margin: 10px auto;
					padding: 10px 0 ;
					list-style: none;
				}
				.box1 ul li{
					margin: 0;
					padding: 20px 0;
				}
				
				.jt{
					display: inline-block;
					border: 5px solid;
					border-color: rgba(0,0,0,.5)   transparent transparent ; /* 上,下,左右 */
					width: 0;
					
				}
			
				#sj1{
					border: 10px solid;
					border-color: transparent  transparent white transparent; /* 上,下,左右 */
					width: 0;
					display: inline-block;
				}
				#alt{
					width: 100px;
					height: 100px;
					background-color:white ;
					margin: -5px 0 auto;
					border: 5px solid white;
					border-radius: 10px;
				}
				#play{
					display: none;
					position: absolute;
					top: 22px;
					left: 63px;
					
				}
				.sz{
					display: block;
					margin: 10px;
				}
				#alt a:hover{
					text-decoration: underline;
				}
				.box2 ul{
					margin: 10;
					padding: 0;
					list-style: none;
				} 
				.box2 ul li{
					margin-top:20px;
				}
		</style>
	</head>
	<body>
		<div id="content">
		<div class="header">
				<h1>This Is Myblog </h1>
		</div>
		<div class="main">
			<div class="box1">
				<ul>
					<li><a href="#">登录</a></li>
					<li><a href="#">注册</a></li>
					<li><a href="http://www.baidu.com">联系</a></li>
					<li><a href="#">帮帮我</a></li>
				</ul>
			</div>
			<div class="box">
				<h2>hello world</h2>
			</div>
			<div class="box2">
				<ul>
					<li>
						<a>设置</a>
						<a href="#" id="sj" class="jt"></a>
					</li>
				<div id="play">
					<div id="sj1"></div>
					<div id="alt">
					<a class="sz" href="#">个人设置</a>
					<a class="sz" href="#">账号中心</a>
					<a class="sz" href="#">退出</a>
					</div>
				</div>
				<li>
					<a>收藏</a>
					<a class="jt"></a>
					
				</li>
			</div>
		</div>
	</div>
	<script src="https://cdn.bootcss.com/jquery/3.3.1/jquery.js"></script>
	<script type="text/javascript">
		var p=$("#play");
		var a=$("#sj");
		
		a.mouseenter(function(){
				p.slideDown(300);
			});
		p.mouseleave(function(){
			p.slideUp(300);
		})
	</script>
	</body>
</html>




