<template lang="pug">
.BOTTON2
	.RESONJOIN 為什麼要參賽?
		.jointext1 讓我們告訴你!
		.joinimg1
	.jointext2 萬眾矚目!
	.jointext3 享受來自整個國家...不,全世界的目光!<br>讓世界看到你!看到台灣!你會是人民的寵兒,國家的驕傲!
	.jointext4 實現夢想!
	.jointext5 我們給予優勝者高額獎金、專業訓練與出道機會!<br>更別提還有跟各天王級導師手把手學習的機會!
	.RESONHELP
	.FLOWER
	.flowerbody
	.flowerfeet1
	.flowerfeet2
	.flower
	.flowerflax1
	.flowerflax2
	.flowerflax3
	.flowerflax4
	.flowerflax5
	.flowerflax6
	.joinlinkkk 
		router-link(tag="joinlinkkk", to="/sorry") >>前往報名!
		.liboxup
		.liboxdown

</template>

<style lang="sass">
.joinlinkkk
	cursor: pointer
	position: absolute
	font-size: 60px
	color: rgb( 220, 220, 220)
	top: 330%
	letter-spacing: 40px
	left: 30%
	z-index: 71
	opacity: 100%
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

.joinlinkkk:hover
	.liboxdown
		opacity: 80%
		height: 10%
		top: 90%
		// border: 1px solid red
	.liboxup
		opacity: 80%
		height: 10%
		top: 0%

// .joinlinkkk
// 	cursor: pointer
// 	position: absolute
// 	font-size: 60px
// 	color: rgb( 220, 220, 220)
// 	top: 330%
// 	letter-spacing: 40px
// 	left: 30%
// 	z-index: 71
// 	opacity: 100%

.BOTTON2
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
.jointext1
	position: absolute
	font-size: 18px
	color: rgb( 220, 220, 220)
	top: 120%
	letter-spacing: 60px
	left: 10%
	z-index: 71

.jointext2
	position: absolute
	font-size: 80px
	color: rgb( 220, 220, 220)
	top: 70%
	letter-spacing: 60px
	left: 32%
	z-index: 71
	opacity: 100%

.jointext3
	position: absolute
	font-size: 18px
	color: rgb( 220, 220, 220)
	top: 150%
	letter-spacing: 10px
	left: 28%
	z-index: 71
	opacity: 100%

.jointext4
	position: absolute
	font-size: 80px
	color: rgb( 220, 220, 220)
	top: 190%
	letter-spacing: 60px
	left: 33%
	z-index: 71
	opacity: 100%

.jointext5
	position: absolute
	font-size: 18px
	color: rgb( 220, 220, 220)
	top: 300%
	letter-spacing: 10px
	left: 30%
	z-index: 71
	opacity: 100%

.flowerbody
	position: absolute
	background: rgb( 220, 220, 220)
	width: 6%
	height: 10%
	border-radius: 1000px
	top: 290%
	left: 47%
	z-index: 71
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s
.flowerfeet1
	position: absolute
	background: rgb( 220, 220, 220)
	width: 6%
	height: 10%
	border-radius: 1000px
	top: 290%
	left: 47%
	z-index: 71
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s
.flowerfeet2
	position: absolute
	background: rgb( 220, 220, 220)
	width: 6%
	height: 10%
	border-radius: 1000px
	top: 290%
	left: 47%
	z-index: 71
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s
.flower
	position: absolute
	background: rgb( 220, 220, 220)
	width: 6%
	height: 10%
	border-radius: 1000px
	top: 290%
	left: 47%
	z-index: 71
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s
.flowerflax1
	position: absolute
	background: rgb( 220, 220, 220)
	width: 6%
	height: 10%
	border-radius: 1000px
	top: 290%
	left: 47%
	z-index: 71
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s
.flowerflax2
	position: absolute
	background: rgb( 220, 220, 220)
	width: 6%
	height: 10%
	border-radius: 1000px
	top: 290%
	left: 47%
	z-index: 71
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s
.flowerflax3
	position: absolute
	background: rgb( 220, 220, 220)
	width: 6%
	height: 10%
	border-radius: 1000px
	top: 290%
	left: 47%
	z-index: 71
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s
.flowerflax4
	position: absolute
	background: rgb( 220, 220, 220)
	width: 6%
	height: 10%
	border-radius: 1000px
	top: 290%
	left: 47%
	z-index: 71
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s
.flowerflax5
	position: absolute
	background: rgb( 220, 220, 220)
	width: 6%
	height: 10%
	border-radius: 1000px
	top: 290%
	left: 47%
	z-index: 71
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s
.flowerflax6
	position: absolute
	background: rgb( 220, 220, 220)
	width: 6%
	height: 10%
	border-radius: 1000px
	top: 290%
	left: 47%
	z-index: 71
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s

.FLOWER
	position: absolute
	background: rgba( 220, 220, 220, 0)
	width: 100%
	height: 90%
	// border-radius: 1000px
	top: 215%
	// border: 1px solid red
	left: 0%
	z-index: 75

.FLOWER:hover~.flower
		position: absolute
		background: #ffc971
		width: 15%
		height: 30%
		border-radius: 200px
		top: 221%
		left: 42.5%
		z-index: 73
.FLOWER:hover~.flowerbody
		position: absolute
		background: #2f3e46
		width: 1.5%
		height: 40%
		top: 250%
		left: 49.3%
		z-index: 72

.FLOWER:hover~.flowerflax1
		position: absolute
		background: #ff97b7
		width: 8%
		height: 10%
		border-radius: 1000px
		top: 240%
		left: 33%
		z-index: 74
		-moz-transform: rotate(-20deg)
		-webkit-transform: rotate(-20deg)
		-o-transform: rotate(-20deg)
		-ms-transform: rotate(-20deg)
		transform: rotate(-20deg)

.FLOWER:hover~.flowerflax2
		position: absolute
		background: #ff5d8f
		width: 8%
		height: 11%
		border-radius: 1000px
		top: 215%
		left: 35%
		z-index: 74
		-moz-transform: rotate(30deg)
		-webkit-transform: rotate(30deg)
		-o-transform: rotate(30deg)
		-ms-transform: rotate(30deg)
		transform: rotate(30deg)

.FLOWER:hover~.flowerflax3
		position: absolute
		background: #ff97b7
		width: 8%
		height: 9%
		border-radius: 1000px
		top: 208%
		left: 50%
		z-index: 74
		-moz-transform: rotate(110deg)
		-webkit-transform: rotate(110deg)
		-o-transform: rotate(110deg)
		-ms-transform: rotate(110deg)
		transform: rotate(110deg)

.FLOWER:hover~.flowerflax4
		position: absolute
		background: #ff97b7
		width: 8%
		height: 10%
		border-radius: 1000px
		top: 228%
		left: 59%
		z-index: 74
		-moz-transform: rotate(165deg)
		-webkit-transform: rotate(165deg)
		-o-transform: rotate(165deg)
		-ms-transform: rotate(165deg)
		transform: rotate(165deg)

.FLOWER:hover~.flowerflax5
		position: absolute
		background: #ff5d8f
		width: 8%
		height: 10%
		border-radius: 1000px
		top: 249%
		left: 55%
		z-index: 74
		-moz-transform: rotate(225deg)
		-webkit-transform: rotate(225deg)
		-o-transform: rotate(225deg)
		-ms-transform: rotate(225deg)
		transform: rotate(225deg)

.FLOWER:hover~.flowerflax6
		position: absolute
		background: #ff97b7
		width: 8%
		height: 10%
		border-radius: 1000px
		top: 256%
		left: 43%
		z-index: 74
		-moz-transform: rotate(-70deg)
		-webkit-transform: rotate(-70deg)
		-o-transform: rotate(-70deg)
		-ms-transform: rotate(-70deg)
		transform: rotate(-70deg)

.FLOWER:hover~.flowerfeet1
		position: absolute
		background: #4c956c
		width: 1%
		height: 45%
		top: 255.2%
		left: 39.5%
		z-index: 71
		-moz-transform: rotate(-60deg)
		-webkit-transform: rotate(-60deg)
		-o-transform: rotate(-60deg)
		-ms-transform: rotate(-60deg)
		transform: rotate(-60deg)

.FLOWER:hover~.flowerfeet2
		position: absolute
		background: #4c956c
		width: 1%
		height: 45%
		top: 255.3%
		left: 59.5%
		z-index: 71
		-moz-transform: rotate(60deg)
		-webkit-transform: rotate(60deg)
		-o-transform: rotate(60deg)
		-ms-transform: rotate(60deg)
		transform: rotate(60deg)

// .joinimg1
// 	position: absolute
// 	width: 48%
// 	height: 56%
// 	top: 60%
// 	left: 26%
// 	z-index: 71
// 	opacity: 80%
// 	// border: solid red 1px
// 	background-size: cover
// 	background-image: url('https://upload.cc/i1/2021/01/25/3L2pWw.png')
// 	// animation-name: moveup
// 	animation-duration: 20s
// 	animation-iteration-count: infinite
// 	animation-fill-mode: both
// 	animation-timing-function: ease-in-out
</style>