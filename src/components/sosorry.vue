<template lang="pug">
.sosorry

	.sorrytitle 很遺憾...
		.sorrytext 本期大叔訓練生已滿,<br>隨時關注官網把握下次機會喔!
	.face
	.tear1
	.tear2
	.tear3
	.tear4

</template>

<style lang="sass">


.tear2
	position: absolute
	background: #48cae4
	width: 4%
	height: 30%
	border-radius: 1000px
	top: 107%
	opacity: 80%
	left: 54%
	z-index: 99
	animation-name: tear
	animation-duration: 2s
	animation-delay: 0.1s
	animation-timing-function: ease-in-out
	animation-play-state: running
	animation-iteration-count: infinite


.tear1
	position: absolute
	background: #48cae4
	width: 4%
	height: 30%
	border-radius: 1000px
	top: 108%
	opacity: 80%
	left: 43.5%
	z-index: 99
	animation-name: tear
	animation-duration: 2s
	animation-timing-function: ease-in-out
	animation-play-state: running
	animation-iteration-count: infinite

@keyframes tear
	0%
		top: 107%
		height: 0%
		width: 4%
	
	
	25%
		top: 107%
		height: 30%
		width: 4%

	
	100%
		top: 190%
		height: 0%
		width: 4%


.sosorry
	font-family: Microsoft YaHei

.face
	position: absolute
	// border: 1px solid red
	top: 80%
	left: 35%
	width: 29.7%
	height: 60%
	z-index: 99
	opacity: 100%
	background-image: url('https://upload.cc/i1/2021/01/26/lsmpCd.png')
	background-size: contain

.sorrytitle
	position: absolute
	font-size: 60px
	color: rgb( 220, 220, 220)
	top: 40%
	letter-spacing: 40px
	left: 40%
	z-index: 71
	opacity: 100%

.sorrytext
	position: absolute
	font-size: 18px
	color: rgb( 220, 220, 220)
	top: 100%
	width: 150%
	letter-spacing: 30px
	left: -25%
	z-index: 71
	opacity: 100%

</style>