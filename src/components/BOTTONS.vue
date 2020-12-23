<template lang="pug">
.titleFlex
	.secbotton
		.title 最新消息
		.text 活動與獲獎
		.seccontentsha
		.seccontent
			.TITLE 院學士班最新訊息
			.SUBTITLE 新消息，看這裡！
			.PIC
			.PIC
			.PIC
			.PIC
			.PIC

	
	.fstbotton
		.iimmg
		.title 學士班
		.text 特色與核心
		.contentsha
		.content
			.TITLE1 學士班特色
				.TEXT 清華是國際頂尖科技大學，加上合校後的藝術學院，<br>具備發展「科技藝術」的卓越條件。<br>我們號召臺灣年輕一代的科技藝術學者專家，我們規劃有科技藝術跨域特別課程，並與業界合作推出創意跨域專題。<br>你，不需猶豫，歡迎你的加入！
			.TITLE2 核心能力
				.TEXT 社會關懷與品格實踐能力｜美感認知與經典欣賞能力｜自然感知與創新發想能力<br>邏輯思辨與語文溝通能力｜國際觀點與在地行動能力｜資訊掌握與科技應用能力
			.TEXT1 清華大學2018年成立藝術學院〝科技藝術〞跨域「學士班」。<br>「科技藝術（TechArt）」是當代藝術的新形式創作也是國際藝術發展的重要趨勢，包含虛擬藝術、互動藝術、電腦動畫、電腦音樂、聲音藝術、科技性表演藝術、混合藝術、網路社群、創客藝術、仿生藝術、生物藝術、人工生命…等。<br>在當代數位美學與數位藝術的基礎下，我們結合創新科技，如各種互動感測技術、虛擬實境、物聯網、人工智慧、大數據分析、基因工程…，把「科技」與「藝術」結合視為「未來文化學」，培養前瞻性、跨域研究與創作人才。
			.TEXT2 因應未來產業的發展趨勢，創新科技與當代藝術結合之創作如雨後春筍。<br>本班師資除來自清華校內藝術學院、電資學院、工學院、生命科學院、人文社會等跨域教師外，我們也將聘進一群來自美國、歐洲與日本跨國與跨域的專業教師。<br>同時廣邀在臺灣在科技藝術創作領域最頂尖的業界團隊與藝術家加入我們的教學團隊，讓同學得到專業與多元的指導，並在共享學習、共享創意的環境裡，開創未來的產業，盡情發揮自己的潛能。
	.iimmg1
	.iimmg2
</template>

<style lang="sass">
.fstbotton
	display: flex
	flex-direction: column
	//border: 1px solid red
	position: fixed
	width: 9.2%
	height: 18.4%
	left: 45.4%
	top: 30.8%
	opacity: 100%
	color: rgba(0, 0, 0, 1)
	background-image: url('https://upload.cc/i1/2020/12/21/VgjUdM.jpg')
	background-size: 102% 102%
	z-index: 10
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s

.iimmg1
	position: fixed
	width: 10%
	height: 20%
	left: 45%
	top: 30%
	opacity: 60%
	background-image: url('https://upload.cc/i1/2020/12/21/VgjUdM.jpg')
	background-size: 100% 100%
	z-index: 1

.content
	display: block
	opacity: 100%
	font-size: 0px
	background-color: white
	border-radius: 50px
	color: rgba(0,0 ,0 ,0 )
	box-shadow: rgba(0, 0, 0, 0.35) 0px 400px 50px
	top: 30%
	left: 45%
	width: 10%
	height: 0%
	z-index:10
	position: fixed
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.contentsha
	display: block
	opacity: 100%
	font-size: 0px
	background-color: white
	border-radius: 50px
	color: rgba(0,0 ,0 ,0 )
	box-shadow: rgba(0, 0, 0, 0.4) 0px 30px 40px
	top: 30%
	left: 45%
	width: 10%
	height: 0%
	z-index:10
	position: fixed
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.TITLE1
	position: relative
	top: 0%
	font-size: 0px
	opacity: 0
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s
.TITLE2
	position: relative
	font-size: 0px
	opacity: 0
	top: 0%
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s
.TEXT
	border: 20px solid rgba(0, 0, 0, 0)
	font-size: 0px
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.TEXT1
	position: relative
	border: solid rgba(0, 0, 0, 0)
	border-width: 20px 40px 10px 40px
	font-size: 0px
	top: 0%
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
	top: 0%
	opacity: 0
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.title
	position: relative
	top: 40%

.text
	position: relative
	top: 40%

.secbotton
	display: flex
	flex-direction: column
	//border: 1px solid red
	position: fixed
	width: 9.2%
	height: 18.4%
	left: 45.4%
	top: 60.8%
	color: rgba(0, 0, 0, 1)
	opacity: 100%
	background-image: url('https://upload.cc/i1/2020/12/21/HquOZE.jpg')
	background-size: 102% 102%
	z-index: 20
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s

.iimmg2
	position: fixed
	width: 10%
	height: 20%
	left: 45%
	top: 60%
	opacity: 60%
	background-image: url('https://upload.cc/i1/2020/12/21/HquOZE.jpg')
	background-size: 100% 100%
	z-index: 1

.seccontent
	display: block
	opacity: 100%
	font-size: 0px
	background-color: white
	border-radius: 50px
	color: rgba(0,0 ,0 ,0 )
	box-shadow: rgba(0, 0, 0, 0.35) 0px 300px 50px
	top: 60%
	left: 45%
	width: 10%
	height: 0%
	z-index:10
	position: fixed
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.seccontentsha
	display: block
	opacity: 100%
	font-size: 0px
	background-color: white
	border-radius: 50px
	color: rgba(0,0 ,0 ,0 )
	box-shadow: rgba(0, 0, 0, 0.4) 0px 30px 40px
	top: 60%
	left: 45%
	width: 10%
	height: 0%
	z-index:10
	position: fixed
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.TITLE
	position: relative
	top: 0%
	font-size: 0px
	opacity: 0
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
.SUBTITLE
	border: 20px solid rgba(0, 0, 0, 0)
	font-size: 0px
	top: 0%
	opacity: 0
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.PIC
	border: 20px solid rgba(0, 0, 0, 1)
	font-size: 0px
	top: 0%
	opacity: 0
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.fstbotton:hover
	
	width: 60%
	height: 100%
	left: 20%
	top: 0%
	z-index: 25
	opacity: 90%
	color: rgba(0, 0, 0, 0)
	.content
		top: 15%
		width: 40%
		height: 90vh
		display: block
		opacity: 90%
		left: 30%
		font-size: 20px
		z-index: 25
		color: rgba(0,0 ,0 ,1 )
		// transition-property: opacity, width ,height
		// transition-duration: 1s
		// transition-timing-function: ease-out
		// -webkit-transition-property: opacity, width ,height
		// -webkit-transition-duration: 1s
		// -o-transition-property: opacity, width ,height
		// -o-transition-duration: 1s

	.contentsha
		top: 15%
		width: 40%
		height: 90vh
		display: block
		opacity: 90%
		left: 30%
		font-size: 20px
		z-index: 20
		color: rgba(0,0 ,0 ,1 )

	.TITLE1
		position: relative
		top: 3%
		opacity: 100
		font-size: 20px
	.TITLE2
		position: relative
		top:3%
		opacity: 100
		font-size: 20px
	.TEXT
		font-size: 15px
	.TEXT1
		position: relative
		opacity: 100
		font-size: 14px
		top: 4%
	.TEXT2
		position: relative
		opacity: 100
		font-size: 14px
		top:2%

.secbotton:hover
	
	width: 60%
	height: 100%
	left: 20%
	top: 0%
	z-index:20
	opacity: 90%
	color: rgba(0, 0, 0, 0)
	.seccontent
		top: 15%
		width: 40%
		height: 90vh
		display: block
		opacity: 90%
		left: 30%
		font-size: 20px
		z-index: 20
		color: rgba(0,0 ,0 ,1 )
		// transition-property: opacity, width ,height
		// transition-duration: 1s
		// transition-timing-function: ease-out
		// -webkit-transition-property: opacity, width ,height
		// -webkit-transition-duration: 1s
		// -o-transition-property: opacity, width ,height
		// -o-transition-duration: 1s

	.seccontentsha
		top: 15%
		width: 40%
		height: 90vh
		display: block
		opacity: 90%
		left: 30%
		font-size: 20px
		z-index: 20
		color: rgba(0,0 ,0 ,1 )

	.TITLE
		position: relative
		top: 3%
		opacity: 100
		font-size: 20px
	.SUBTITLE
		border: 20px solid rgba(0, 0, 0, 0)
		position: relative
		opacity: 100
		top: 3%
		font-size: 10px
	.PIC
		border: 20px solid rgba(0, 0, 0, 1)
		position: relative
		opacity: 100
		top: 3%
		font-size: 10px
	
</style>