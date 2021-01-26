<template lang="pug">
.titleFlex

	.Banner
	.Banercapt
		.line1
		.line2
		.line3
		.line4
		.word1 分子
		.word2 大叔

	.title2 節目簡介 
		.content
			.TEXT1r 賽期共計100天。在此期間，100多位訓練生將在《分子大叔》的舞台上接受公益活動、藝術專業、大眾認可三個方向的考核，努力成長為有理想、有本領、有擔當的新時代中年。<br>大叔製作人代表與導師團透過表現將成員進行分級並給予訓練，而節目觀眾將作為大叔製作人，<br>登入節目平台帳號為心儀的訓練生進行助力，決選出最終的9人組合出道。<br>每期投票結果將於當期節目結束前公布。

	.title1 什麼是分子大叔 ？
		.content
			.TEXT1 是2021年推出的偶像團體競演養成類真人秀節目，本季節目為大叔選秀。<br>節目賽制是從各家經紀公司或練習生公司選出109位參賽者，在4個多月中進行封閉式的訓練及錄制，<br>最終由大叔製作人們的助力結果選出9人組成全新偶像團體「OLD9」出道。<br>2021年1月15日，節目正式定檔於3月12日起每周四、六20:00不會播出。
	.title3 參與節目！
		.content
			.TEXT1 您可以透過成為大叔直接參加節目！也可以透過成為大叔製作人來為你的大叔助力！
			.TEXT2 > 成為大叔
			.TEXT3 
				router-link(tag="TEXT3", to="/rules") > 成為製作人


	.title4 如何助力 ?
		.content
			.TEXT1r 助力規則如下
			.TEXT4 第一與第二階段助力（第一期至第七期）：<br>

				<br>登陸帳號，普通用戶每天擁有一次助力機會，每次可為9位訓練生助力，不可重複選擇同一訓練生。
				<br>VIP用戶每天額外擁有一次助力機會，每次可為9位訓練生助力，不可重複選擇同一訓練生。
				<br>打開APP，進入助力通道，每天額外擁有一次助力機會。每次可為9位訓練生助力，<br>不可重複選擇同一訓練生。
				<br>加入官方唯一助力小程序——真果粒大叔福利社，獲得更多助力機會，支持公益活動。<br>
			.TEXT1r 助力規則會隨節目進程改變，記得隨時關注官方網站喔 !

	.title5 參與？WHY ?
		.content
			.TEXT1 參加、助力能帶來什麼好處呢？讓我們來告訴您 !
			.TEXT5 > 前往瞭解
	.entryanima
	.runthru 宇宙是由分子組成的,這群大叔---也是。 宇宙最強男團選拔《分子大叔  MOLU UNCLE》星艦即將啟航， 請儘速報名航向新星!
	.runthru2 宇宙是由分子組成的,這群大叔---也是。 宇宙最強男團選拔《分子大叔  MOLU UNCLE》星艦即將啟航， 請儘速報名航向新星!
</template>

<style lang="sass">

.runthru2
	position: absolute
	font-size: 20px
	top: 45%
	left: 150%
	width: 100%
	color: white
	z-index: 80
	letter-spacing: 5px
	animation-name: passby2
	animation-delay: 17s
	animation-duration: 35s
	animation-timing-function: linear
	animation-play-state: running
	animation-iteration-count: infinite


@keyframes passby2
	0%
		left: 100%
	
	50%
		left: 0%

	100%
		left: -100%

.runthru
	position: absolute
	font-size: 20px
	top: 45%
	left: 25%
	color: white
	z-index: 80
	width: 100%
	animation-name: passby1
	letter-spacing: 5px
	animation-duration: 35s
	animation-timing-function: linear
	animation-play-state: running
	animation-iteration-count: infinite


@keyframes passby1
	0%
		left: 100%
	
	
	50%
		left: 0%

	100%
		left: -100%


.titleFlex
	font-family: Microsoft YaHei

// .Banercapt
// 	position: absolute
// 	height: 1%
// 	width: 14%
// 	top: 25%
// 	left: 19%
// 	background: rgb( 255, 255, 255)
// 	z-index: 11
// 	border: 1px solid red

.line3	
	position: absolute
	height: 0.3%
	width: 10%
	top: 41%
	left: 69.5%
	background: rgb( 255, 255, 255)
	z-index: 11

	
.word2
	position: absolute
	font-size: 27px
	top: 38.5%
	left: 65%
	color: white
	z-index: 11

	
.line2
	position: absolute
	height: 0.3%
	width: 22.5%
	top: 41%
	left: 41.5%
	background: rgb( 255, 255, 255)
	z-index: 11

.word1
	position: absolute
	font-size: 27px
	top: 38.5%
	left: 37%
	color: white
	z-index: 11
.line1
	position: absolute
	height: 0.3%
	width: 16%
	top: 41%
	left: 20%
	background: rgb( 255, 255, 255)
	z-index: 11
	// border: 1px solid red
.Banner
	position: absolute
	top: 20%
	left: 19%
	width: 60%
	height: 15%
	background-image: url('https://upload.cc/i1/2021/01/23/W2NqkI.png')
	background-size: contain
	// border: 1px solid red
	display: flex
	flex-direction: column
	// border-radius: 50px
	z-index: 10
	opacity: 100%
	box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 30px
	
.title1
	position: absolute
	top: 65%
	left: 10%
	// font-weight: bold
	color: rgb( 190, 190, 190)
	font-size: 60px
	box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 30px
	display: flex
	flex-direction: column
	//border: 1px solid red
	opacity: 100%
	border-radius: 50px
	// background-image: url('https://upload.cc/i1/2020/12/21/VgjUdM.jpg')
	z-index: 99
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s

.title2
	position: absolute
	top: 65%
	right: 10%
	// font-weight: bold
	color: rgb( 190, 190, 190)
	font-size: 60px
	box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 30px
	display: flex
	flex-direction: column
	//border: 1px solid red
	opacity: 100%
	border-radius: 50px
	// background-image: url('https://upload.cc/i1/2020/12/21/VgjUdM.jpg')
	z-index: 99
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s

.title3
	position: absolute
	top: 105%
	left: 10%
	// font-weight: bold
	color: rgb( 190, 190, 190)
	font-size: 60px
	box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 30px
	display: flex
	flex-direction: column
	//border: 1px solid red
	opacity: 100%
	border-radius: 50px
	// background-image: url('https://upload.cc/i1/2020/12/21/VgjUdM.jpg')
	z-index: 99
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s

.title4
	position: absolute
	top: 105%
	right: 10%
	// font-weight: bold
	color: rgb( 190, 190, 190)
	font-size: 60px
	box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 30px
	display: flex
	flex-direction: column
	//border: 1px solid red
	opacity: 100%
	border-radius: 50px
	// background-image: url('https://upload.cc/i1/2020/12/21/VgjUdM.jpg')
	z-index: 99
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s

.title5
	position: absolute
	top: 145%
	left: 37%
	// font-weight: bold
	color: rgb( 190, 190, 190)
	font-size: 60px
	box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 30px
	display: flex
	flex-direction: column
	//border: 1px solid red
	opacity: 100%
	border-radius: 50px
	// background-image: url('https://upload.cc/i1/2020/12/21/VgjUdM.jpg')
	z-index: 99
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s

.content
	display: block
	opacity: 100%
	font-size: 0px
	border-radius: 50px
	color: rgba(0,0 ,0 ,0 )
	box-shadow: rgba(0, 0, 0, 0.35) 0px 400px 50px
	top: 0%
	left: 0%
	text-align: justify
	// text-justify: inter-ideograph
	width: 100%
	height: 0%
	z-index:10
	position: absolute
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 0.5s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s


.TEXT1
	position: relative
	border: solid rgba(0, 0, 0, 0)
	border-width: 20px 40px 10px 40px
	font-size: 0px
	z-index: 10
	top: 0%
	opacity: 0
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.TEXT1r
	position: relative
	border: solid rgba(0, 0, 0, 0)
	border-width: 20px 40px 10px 40px
	font-size: 0px
	z-index: 10
	top: 0%
	text-align: right
	opacity: 0
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.TEXT2
	position: relative
	border: solid rgba(0, 0, 0, 0)
	border-width: 20px 40px 10px 40px
	font-size: 0px
	z-index: 10
	top: 0%
	opacity: 0
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.TEXT3
	position: relative
	border: solid rgba(0, 0, 0, 0)
	border-width: 20px 40px 10px 40px
	font-size: 0px
	z-index: 10
	cursor: pointer
	top: 0%
	opacity: 0
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.TEXT4
	position: relative
	border: solid rgba(0, 0, 0, 0)
	border-width: 20px 40px 10px 40px
	font-size: 0px
	z-index: 10
	top: 0%
	left: 0%
	text-align: right
	opacity: 0
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.TEXT5
	position: relative
	border: solid rgba(0, 0, 0, 0)
	border-width: 20px 40px 10px 40px
	font-size: 0px
	z-index: 10
	top: 0%
	left: 0%
	text-align: left
	opacity: 0
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.title1:hover
	
	z-index: 99
	opacity: 100%
	top: 60%
	color: rgb( 255, 255, 255)
	box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 30px
	.content
		top: 100%
		width: 200%
		display: block
		left: -6%
		opacity: 100%
		font-size: 50px
		z-index: 25
		color: rgba(255 , 255, 255, 1)
		text-align: left

	.TEXT1
		position: relative
		opacity: 100
		font-size: 20px
		top: 4%


		
.title2:hover
	color: #fcefb4
	z-index: 99
	opacity: 100%
	top: 60%
	box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 30px
	.content
		text-align: right
		top: 100%
		left: -280%
		width: 400%
		display: block
		opacity: 100%
		font-size: 20px
		z-index: 25
		color: rgba(255 , 255, 255, 1)

	.TEXT1r
		position: relative
		opacity: 100%
		font-size: 20px
		top: 4%
		z-index: 25

.title2:hover~.title1
	top: 90%

.title2:hover~.title3
	top: 110%

.title3:hover
	
	z-index: 99
	opacity: 100%
	top: 100%
	color: #caf0f8
	box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 30px
	.content
		top: 100%
		width: 300%
		display: block
		left: -10%
		opacity: 100%
		font-size: 50px
		z-index: 25
		color: rgba(255 , 255, 255, 1)
		text-align: justify

	.TEXT1
		position: relative
		opacity: 100
		font-size: 20px
		top: 4%

	.TEXT2
		position: relative
		opacity: 100
		font-size: 30px
		top: 4%

	.TEXT3
		position: relative
		opacity: 100
		font-size: 30px
		top: 4%

.title4:hover
	color: #ffcad4
	z-index: 99
	opacity: 100%
	top: 100%
	box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 30px
	.content
		text-align: right
		top: 100%
		left: -285%
		width: 400%
		display: block
		opacity: 100%
		font-size: 20px
		z-index: 25
		color: rgba(255 , 255, 255, 1)

	.TEXT1r
		position: relative
		opacity: 100%
		font-size: 25px
		top: 4%
		z-index: 25

	.TEXT4
		position: relative
		opacity: 100
		font-size: 20px
		top: 4%
		left: 0%

.title4:hover~.title5
	top: 160%

.title5:hover
	
	z-index: 99
	opacity: 100%
	top: 140%
	color: #edc4b3
	box-shadow: rgba(0, 0, 0, 0.4) 0px 0px 30px
	.content
		top: 100%
		width: 200%
		display: block
		left: -8%
		opacity: 100%
		font-size: 50px
		z-index: 25
		color: rgba(255 , 255, 255, 1)

	.TEXT1
		position: relative
		opacity: 100
		font-size: 20px
		top: 4%

	.TEXT5
		position: relative
		opacity: 100
		font-size: 30px
		top: 4%

</style>