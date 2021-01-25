<template lang="pug">
.slides
	.slide1L
	.slide1r
	.slide2L
	.slide2r
	.block1
	.TITLE1 暫定導師名單出爐!
	.TITLE2 首次快閃表演場地出爐!
	.textt (圖片非當事導師)
	.textt2 (圖片非表演場地)

</template>

<style lang="sass">
.slides
	font-family: Microsoft YaHei

.textt
	position: absolute
	z-index: 4
	left: 35.5%
	top: 245%
	font-size: 15px
	color: rgb( 200, 200, 200)
	text-align: center
	letter-spacing: 40px
	animation-name: textt
	animation-duration: 20s
	animation-iteration-count: infinite
	animation-fill-mode: both
	animation-timing-function: ease-in-out

.textt2
	position: absolute
	z-index: 4
	left: 35.5%
	top: 245%
	color: rgb( 200, 200, 200)
	font-size: 15px
	text-align: center
	letter-spacing: 40px
	animation-name: textt2
	animation-duration: 20s
	animation-iteration-count: infinite
	animation-fill-mode: both
	animation-timing-function: ease-in-out

.TITLE2
	position: absolute
	z-index: 4
	left: 28%
	top: 186%
	color: rgb( 200, 200, 200)
	font-size: 52px
	letter-spacing: 14px
	text-align: center
	animation-name: TITLE2
	animation-duration: 20s
	animation-iteration-count: infinite
	animation-fill-mode: both
	animation-timing-function: ease-in-out

.TITLE1
	position: absolute
	z-index: 4
	left: 28%
	top: 186%
	color: rgb( 200, 200, 200)
	font-size: 52px
	letter-spacing: 30px
	text-align: center
	animation-name: TITLE1
	animation-duration: 20s
	animation-iteration-count: infinite
	animation-fill-mode: both
	animation-timing-function: ease-in-out
.block1
	position: absolute
	z-index: 3
	top: 185%
	left: 27.7%
	width: 44.6%
	height: 15%
	background-color: rgb( 10, 10, 10)
	animation-name: nomovbutchange
	animation-duration: 20s
	animation-iteration-count: infinite
	animation-fill-mode: both
	animation-timing-function: ease-in-out

.slide1L
	position: absolute
	top: 200%
	right: 50%
	// border: solid red 1px
	background-size: cover
	background-image: url('https://upload.cc/i1/2021/01/24/o5FiVw.png')
	animation-name: moveup
	animation-duration: 20s
	animation-iteration-count: infinite
	animation-fill-mode: both
	animation-timing-function: ease-in-out

.slide1r
	position: absolute
	z-index: 2
	top: 200%
	left: 50%
	width: 22.3%
	height: 40%
	// border: solid red 1px
	background-size: cover
	background-image: url('https://upload.cc/i1/2021/01/24/eKHnkM.png')
	animation-name: movedown
	animation-duration: 20s
	animation-iteration-count: infinite
	animation-fill-mode: both

.slide2L
	position: absolute
	top: 200%
	right: 50%
	// border: solid red 1px
	background-size: cover
	background-image: url('https://upload.cc/i1/2021/01/24/i9JCUj.png')
	animation-name: moveup2
	animation-duration: 20s
	animation-iteration-count: infinite
	animation-fill-mode: both
	animation-timing-function: ease-in-out

.slide2r
	position: absolute
	z-index: 2
	top: 200%
	left: 50%
	width: 22.3%
	height: 40%
	// border: solid red 1px
	background-size: cover
	background-image: url('https://upload.cc/i1/2021/01/24/cg1P8u.png')
	animation-name: movedown2
	animation-duration: 20s
	animation-iteration-count: infinite
	animation-fill-mode: both

@keyframes textt2
	0%
		z-index: 3
		left: 35.5%
		top: 245%
		opacity: 0%
		font-size: 0px
	45%
		z-index: 3
		top: 249%
		opacity: 0%
		left: 36.5%
		font-size: 0px
	49%
		z-index: 4
		top: 244%
		left: 35.5%
		opacity: 100%
		font-size: 15px
	50%
		z-index: 4
		top: 245%
		left: 35.5%
		opacity: 100%
		font-size: 15px

	95%
		z-index: 4
		top: 245%
		left: 35.5%
		opacity: 100%
		font-size: 15px
	100%
		z-index: 3
		top: 240%
		left: 36.5%
		opacity: 0%
		font-size: 0px

@keyframes textt
	0%
		z-index: 4
		left: 35.5%
		top: 245%
		opacity: 100%
		font-size: 15px
	45%
		z-index: 4
		top: 245%
		left: 35.5%
		opacity: 100%
		font-size: 15px
	49%
		z-index: 3
		top: 240%
		left: 36.5%
		opacity: 0%
		font-size: 0px
	
	95%
		z-index: 3
		top: 249%
		opacity: 0%
		left: 36.5%
		font-size: 0px

	99%
		z-index: 4
		top: 244%
		left: 35.5%
		opacity: 100%
		font-size: 15px
	100%
		z-index: 4
		top: 245%
		left: 35.5%
		opacity: 100%
		font-size: 15px

@keyframes TITLE2
	0%
		z-index: 3
		top: 200%
		opacity: 0%
		left: 44%
		font-size: 0px
	45%
		z-index: 3
		top: 200%
		opacity: 0%
		left: 44%
		font-size: 0px
	49%
		z-index: 4
		top: 186%
		left: 28%
		opacity: 100%
		font-size: 52px
	50%
		z-index: 4
		top: 187%
		left: 28%
		opacity: 100%
		font-size: 52px
	
	95%
		z-index: 4
		top: 187%
		left: 28%
		opacity: 100%
		font-size: 52px
	100%
		z-index: 3
		top: 185%
		left: 44%
		opacity: 0%
		font-size: 0px

@keyframes TITLE1
	0%
		z-index: 4
		top: 187%
		left: 28%
		opacity: 100%
		font-size: 52px
	45%
		z-index: 4
		top: 187%
		left: 28%
		opacity: 100%
		font-size: 52px
	49%
		z-index: 3
		top: 185%
		left: 44%
		opacity: 0%
		font-size: 0px
	
	95%
		z-index: 3
		top: 200%
		opacity: 0%
		left: 44%
		font-size: 0px

	99%
		z-index: 4
		top: 186%
		left: 28%
		opacity: 100%
		font-size: 52px
	100%
		z-index: 4
		top: 187%
		left: 28%
		opacity: 100%
		font-size: 52px

@keyframes moveup
	0%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 40%
	45%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 40%
		opacity: 100%
	51%
		z-index: 2
		top: 185%
		width: 22.3%
		height: 0%
		opacity: 100%
	
	95%
		z-index: 2
		top: 240%
		width: 22.3%
		height: 0%
		opacity: 100%
	99%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 40%
		opacity: 100%
	100%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 40%
		opacity: 100%

@keyframes moveup2
	0%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 0%
	45%
		z-index: 2
		top: 240%
		width: 22.3%
		height: 0%
		opacity: 100%

	49%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 40%
		opacity: 100%
	
	95%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 40%
		opacity: 100%

	100%
		z-index: 2
		top: 185%
		width: 22.3%
		height: 0%
		opacity: 100%
		
@keyframes movedown2
	0%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 0%
	45%
		z-index: 2
		top: 185%
		width: 22.3%
		height: 0%
		opacity: 100%
	49%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 40%
		opacity: 100%	
	95%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 40%
		opacity: 100%
	100%
		z-index: 2
		top: 240%
		width: 22.3%
		height: 0%
		opacity: 100%


@keyframes movedown
	0%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 40%
	45%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 40%
		opacity: 100%
	50%
		z-index: 2
		top: 240%
		width: 22.3%
		height: 0%
		opacity: 100%
	
	95%
		z-index: 2
		top: 185%
		width: 22.3%
		height: 0%
		opacity: 100%
	99%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 40%
		opacity: 100%

	100%
		z-index: 2
		top: 200%
		width: 22.3%
		height: 40%
		opacity: 100%


@keyframes nomovbutchange
	0%
		z-index: 3
		top: 185%
		width: 44.6%
		height: 15%
	45%
		z-index: 3
		top: 185%
		width: 44.6%
		height: 15%
	50%
		z-index: 3
		top: 185%
		width: 45%
		height: 15%
		opacity: 100%

	95%
		z-index: 3
		top: 185%
		width: 45%
		height: 15%
		opacity: 100%
	100%
		z-index: 3
		top: 185%
		width: 44.6%
		height: 15%
		opacity: 100%



</style>