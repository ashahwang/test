<!DOCTYPE html>
<html>
<head>
	<title>홈페이지 만들기</title>

<style>
	
.dropdown {
display: inline-block;
}

.dropdown-content{

	display: none;
	position: absolute;
	background-color: orange;
	width:100px; 
	padding: 12px 16px;
}

.dropdown:hover .dropdown-content {
	display: block;
}

*{

	padding: 0;
	margin:0;

}

li{

	list-style-type: none;
}

.clear{

clear:both;

}

header{

	width:1000px;
	heigth:100px;
	margin-top:10px;
	border:solid 1px #cccccc;

}

#logo{

	margin-top: 20px;

float:left;

}

#top {

float:right;
margin:30px 20 px; 0 0;

}

nav{width:1000px;
	height:700px;
	margin-top:10px;
	boder:solid 1px #cccccc;
}



aside{

float:right;
margin-left:30px;
margin-top:10px;
border:solid 1px #cccccc;


}

aside li{

margin-bottom: 20px;

}

footer{
width:1000px;
height:100px;
margin-top:10px;
border:solid 1px #cccccc;


}

#address{

float:left;

 margin 30px 0 0 20px}

}

#costmor{

float:right;
margin:30px 0 0 180px;

}

#page
{

width:1000px;
margin:auto;
border: solid 0px red;

}

</style>

</head>

<body>


<div id='page'>

 <header>

<div id='logo'>

	뱁새

	
	

</div>

<div id='top'>
	<div class="dropdown">

<span>로그인|회원가입|마이페이지|고객센터</span>
<div class="dropdown-content">

</header>

<div class='clear'></div>
<!--float 속성 해제-->

<nav>
	
<ul>
	<li>뱁새</li>
	<li>뱁새프로그램</li>
	<li>뱁새정보</li>
	<li>특별혜택</li>
	<li>이벤트</li>
</ul>
</nav>
<div class='clear'> </div><!--float속성 해제-->
<section>
	
	<img src= babjpg.jpg>

</section>
<aside>

	<ul>


<li>뱁새여행</li>
	<li>핵심혜택</li>
	<li>이벤트</li>
	<li>뱁새 TMI</li>
</ul>

</aside>

<section class = 'clear'> 
<img src="now.jpg" width=1000>
</section>
<div class='clear'></div><!--float 속성 해제-->
<footer>

	<div id='address'>

	주최:뱁새
	주관:뱁새
</div>
 
 <div id='costmor'>

 안내전화:1234
</div>
</footer>

</body>
</html>
