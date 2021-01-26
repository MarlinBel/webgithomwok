<template lang="pug">

.helpbotton

	.RESONJOIN 為什麼要助力?
		.helptext1 讓我們告訴你!
	.helptext2 透過你的一票-
		.helptext11 為分子大叔們添加色彩!
	.helptext3 表達你的意見，和大家一起打造最強戰隊!
	.colorpalat1 
		.colr MERCURY
	.colorpalat2
		.colr2 VENUS
	.colorpalat3
		.colr2 EARTH
	.colorpalat4
		.colr4 MARS
	.colorpalat5
		.colr5 JUPITER
	.colorpalat6
		.colr6 SATURN
	.colorpalat7
		.colr7 URANUS
	.colorpalat8
		.colr NEPTUNE
	.changecolor

	.helptext4 讓你的大叔-
		.helptext111 脫穎而出!


	.shiptrigr
	.ship1
		.fire
	.ship2
		.fire2
	.ship3
		.fire2
	.ship4
		.fire2
	.ship5
		.fire2
	.startline SATRTLINE

	.helptext6 協助你喜愛的選手實現夢想!<br>讓他的努力得到回報!
	
	.helplinkerTO
		router-link(tag="helplinkerTO", to="/rules") >>前往助力!
		.liboxup
		.liboxdown
		


</template>

<style lang="sass">

.helplinkerTO
	cursor: pointer
	position: absolute
	font-size: 52px
	top: 395%
	height: 9%
	// border: 1px solid red
	left: 35%
	letter-spacing: 30px
	color: rgb( 210, 210, 210)
	z-index: 99
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.6s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.6s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.6s
.liboxup
	position: absolute
	background: rgb( 210, 210, 210)
	z-index: 69
	// border: 1pxs solid red
	width: 100%
	height: 100%
	top: 0%
	left: 0%
	opacity: 0%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.6s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.6s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.6s
.liboxdown
	position: absolute
	background: rgb( 210, 210, 210)
	z-index: 69
	width: 100%
	// border: 1px solid red
	height: 100%
	top: 0%
	left: 0%
	opacity: 0%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.6s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.6s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.6s

.helplinkerTO:hover
	.liboxdown
		opacity: 80%
		height: 10%
		top: 90%
		// border: 1px solid red
	.liboxup
		opacity: 80%
		height: 10%
		top: 0%


.helptext6
	position: absolute
	font-size: 25px
	color: rgb( 220, 220, 220)
	top: 380%
	letter-spacing: 40px
	left: 25%
	z-index: 71


.fire2
	position: absolute
	// border: 1px solid red
	background: rgb( 220, 220, 220)
	top: 98%
	left: 50%
	width: 0%
	height: 0%
	z-index: 72
	animation-name: fire2
	animation-duration: 1s
	animation-timing-function: ease-in-out
	animation-play-state: paused
	animation-iteration-count: infinite

@keyframes fire2
	0%
		height: 0%
		width: 60%
		left: 20%
		opacity: 100%
	
	10%
		height: 30%
		width: 60%
		left: 20%
		opacity: 100%

	
	100%
		height: 0%
		width: 0%
		left: 49.5%
		opacity: 100%

.fire
	position: absolute
	// border: 1px solid red
	background: rgb( 220, 220, 220)
	top: 98%
	left: 50%
	width: 0%
	height: 0%
	z-index: 72
	animation-name: fire1
	animation-duration: 1s
	animation-timing-function: ease-in-out
	animation-play-state: paused
	animation-iteration-count: infinite

@keyframes fire1
	0%
		height: 0%
		width: 70%
		left: 15%
		opacity: 100%
	
	10%
		height: 90%
		width: 70%
		left: 15%
		opacity: 100%

	
	100%
		height: 30%
		width: 0%
		left: 49.5%
		opacity: 100%


.shiptrigr
	position: absolute
	// border: 1px solid red
	top: 250%
	left: 0%
	width: 100%
	height: 70%
	z-index: 72

.shiptrigr:hover~.ship1
	top: 220%
	.fire
		animation-play-state: running
.shiptrigr:hover~.ship2
	top: 300%
	.fire2
		animation-play-state: running
.shiptrigr:hover~.ship3
	top: 280%
	.fire2
		animation-play-state: running
.shiptrigr:hover~.ship4
	top: 290%
	.fire2
		animation-play-state: running
.shiptrigr:hover~.ship5
	top: 285%
	.fire2
		animation-play-state: running


.startline
	position: absolute
	font-size: 20px
	font-weight: bold
	color: rgb( 30, 30, 30)
	background: rgb( 220, 220, 220)
	top: 316.5%
	width: 100%
	height: 3.5%
	letter-spacing: 100px
	left: 0%
	z-index: 70



.ship5
	position: absolute
	// border: 1px solid red
	top: 320%
	left: 85%
	width: 9%
	height: 30%
	z-index: 71
	opacity: 100%
	background-image: url('https://upload.cc/i1/2021/01/26/8t2p0m.png')
	background-size: contain
	transition-property: opacity, width ,height,left,font-size,color,top,z-index, background
	transition-duration: 1s
	transition-timing-function: ease-in-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index,background
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index,background
	-o-transition-duration: 1s

.ship4
	position: absolute
	// border: 1px solid red
	top: 320%
	left: 65%
	width: 9%
	height: 30%
	z-index: 71
	opacity: 100%
	background-image: url('https://upload.cc/i1/2021/01/26/sk4j5Y.png')
	background-size: contain	
	transition-property: opacity, width ,height,left,font-size,color,top,z-index, background
	transition-duration: 1s
	transition-timing-function: ease-in-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index,background
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index,background
	-o-transition-duration: 1s

.ship3
	position: absolute
	// border: 1px solid red
	top: 320%
	left: 5%
	width: 9%
	height: 30%
	z-index: 71
	opacity: 100%
	background-image: url('https://upload.cc/i1/2021/01/26/zNJ9aA.png')
	background-size: contain	
	transition-property: opacity, width ,height,left,font-size,color,top,z-index, background
	transition-duration: 1s
	transition-timing-function: ease-in-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index,background
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index,background
	-o-transition-duration: 1s

.ship2
	position: absolute
	// border: 1px solid red
	top: 320%
	left: 25%
	width: 9%
	height: 30%
	z-index: 71
	opacity: 100%
	background-image: url('https://upload.cc/i1/2021/01/26/HYVflc.png')
	background-size: contain	
	transition-property: opacity, width ,height,left,font-size,color,top,z-index, background
	transition-duration: 1s
	transition-timing-function: ease-in-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index,background
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index,background
	-o-transition-duration: 1s

.ship1
	position: absolute
	// border: 1px solid red
	top: 320%
	left: 45%
	width: 9%
	height: 30%
	z-index: 71
	opacity: 100%
	background-image: url('https://upload.cc/i1/2021/01/26/onzyrx.png')
	background-size: contain
	transition-property: opacity, width ,height,left,font-size,color,top,z-index, background
	transition-duration: 1s
	transition-timing-function: ease-in-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index,background
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index,background
	-o-transition-duration: 1s


.helptext111
	position: absolute
	font-size: 18px
	color: rgb( 220, 220, 220)
	top: 120%
	letter-spacing: 60px
	left: 20%
	z-index: 71

.helptext4
	position: absolute
	font-size: 60px
	color: rgb( 220, 220, 220)
	top: 250%
	letter-spacing: 40px
	left: 30%
	z-index: 71
	opacity: 100%



.colorpalat8:hover
	z-index: 100
.colorpalat8:hover~.changecolor
	position: fixed
	// border: 1px solid red
	top: 0%
	left: 0%
	width: 100%
	height: 100%
	z-index: 99
	background: #4361ee
	opacity: 100%

.changecolor
	position: fixed
	// border: 1px solid red
	top: 0%
	left: 0%
	opacity: 0%
	width: 100%
	height: 100%
	z-index: 0
	// background: rgb( 0, 0, 0)
	transition-property: opacity, width ,height,left,font-size,color,top,z-index, background
	transition-duration: 0.9s
	transition-timing-function: ease-in-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index,background
	-webkit-transition-duration: 0.9s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index,background
	-o-transition-duration: 0.9s

.colorpalat8
	position: absolute
	background: #4361ee
	top: 200%
	left: 30%
	width: 40%
	height: 15%
	z-index: 71
	opacity: 100%
	
.colr
	position: absolute
	font-size: 60px
	top: 12%
	letter-spacing: 24px
	left: 21.5%
	color: white

.colorpalat7
	position: absolute
	background: #000
	top: 185%
	left: 30%
	width: 40%
	height: 15%
	z-index: 71
	opacity: 100%
.colr7
	position: absolute
	font-size: 60px
	top: 12%
	letter-spacing: 24px
	left: 20.5%
	color: white

.colorpalat7:hover
	z-index: 100
.colorpalat7:hover~.changecolor
	position: fixed
	// border: 1px solid red
	top: 0%
	left: 0%
	width: 100%
	height: 100%
	z-index: 99
	background: #000
	opacity: 100%



.colorpalat6
	position: absolute
	background: #fcd0a1
	top: 170%
	left: 30%
	width: 40%
	height: 15%
	z-index: 71
	opacity: 100%
.colr6
	position: absolute
	font-size: 60px
	top: 12%
	letter-spacing: 24px
	left: 21.8%
	color: white

.colorpalat6:hover
	z-index: 100
.colorpalat6:hover~.changecolor
	position: fixed
	// border: 1px solid red
	top: 0%
	left: 0%
	width: 100%
	height: 100%
	z-index: 99
	background: #fcd0a1
	opacity: 100%




.colorpalat5
	position: absolute
	background: #af6032
	top: 155%
	left: 30%
	width: 40%
	height: 15%
	z-index: 71
	opacity: 100%
.colr5
	position: absolute
	font-size: 60px
	top: 12%
	letter-spacing: 25px
	left: 19.5%
	color: white

.colorpalat5:hover
	z-index: 100
.colorpalat5:hover~.changecolor
	position: fixed
	// border: 1px solid red
	top: 0%
	left: 0%
	width: 100%
	height: 100%
	z-index: 99
	background: #af6032
	opacity: 100%


.colorpalat4
	position: absolute
	background: #a53f2b
	top: 140%
	left: 30%
	width: 40%
	height: 15%
	z-index: 71
	opacity: 100%
.colr4
	position: absolute
	font-size: 60px
	top: 12%
	letter-spacing: 50px
	left: 23.5%
	color: white

.colorpalat4:hover
	z-index: 100
.colorpalat4:hover~.changecolor
	position: fixed
	// border: 1px solid red
	top: 0%
	left: 0%
	width: 100%
	height: 100%
	z-index: 99
	background: #a53f2b
	opacity: 100%


.colorpalat3
	position: absolute
	background: #006d77
	top: 125%
	left: 30%
	width: 40%
	height: 15%
	z-index: 71
	opacity: 100%
.colr2
	position: absolute
	font-size: 60px
	top: 12%
	letter-spacing: 40px
	left: 21%
	color: white

.colorpalat3:hover
	z-index: 100
.colorpalat3:hover~.changecolor
	position: fixed
	// border: 1px solid red
	top: 0%
	left: 0%
	width: 100%
	height: 100%
	z-index: 99
	background: #006d77
	opacity: 100%


.colorpalat2
	position: absolute
	background: #ffd100
	top: 110%
	left: 30%
	width: 40%
	height: 15%
	z-index: 71
	opacity: 100%
.colr2
	position: absolute
	font-size: 60px
	top: 12%
	letter-spacing: 40px
	left: 21%
	color: white

.colorpalat2:hover
	z-index: 100
.colorpalat2:hover~.changecolor
	position: fixed
	// border: 1px solid red
	top: 0%
	left: 0%
	width: 100%
	height: 100%
	z-index: 99
	background: #ffd100
	opacity: 100%


.colorpalat1
	position: absolute
	background: #6c757d
	top: 95%
	left: 30%
	width: 40%
	height: 15%
	z-index: 71
	opacity: 100%
.colr
	position: absolute
	font-size: 60px
	top: 12%
	letter-spacing: 20px
	left: 18%
	color: white

.colorpalat1:hover
	z-index: 100
.colorpalat1:hover~.changecolor
	position: fixed
	// border: 1px solid red
	top: 0%
	left: 0%
	width: 100%
	height: 100%
	z-index: 99
	background: #6c757d
	opacity: 100%


.helpbotton
	font-family: Microsoft YaHei

.RESONJOIN
	position: absolute
	font-size: 60px
	color: rgb( 220, 220, 220)
	top: 25%
	letter-spacing: 40px
	left: 30%
	z-index: 71
	opacity: 100%
.helptext1
	position: absolute
	font-size: 18px
	color: rgb( 220, 220, 220)
	top: 120%
	letter-spacing: 60px
	left: 10%
	z-index: 71

.helptext11
	position: absolute
	font-size: 18px
	color: rgb( 220, 220, 220)
	top: 120%
	letter-spacing: 50px
	left: 5%
	z-index: 71

.helptext2
	position: absolute
	font-size: 80px
	color: rgb( 220, 220, 220)
	top: 70%
	letter-spacing: 60px
	left: 25%
	z-index: 71
	opacity: 100%

.helptext3
	position: absolute
	font-size: 18px
	color: rgb( 220, 220, 220)
	top: 220%
	letter-spacing: 20px
	left: 28%
	z-index: 71
	opacity: 100%


</style>