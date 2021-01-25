<template lang="pug">
.TOPSTUFF
	.colu1
	.colu2
	.colu3
	.colu4
	.colubutt
	.Block1
		.litlblockup
		.litlblockdown
		.LINKER1
			router-link(tag="LINKER1", to="/") 主頁
	.Block2
		.litlblockup2
		.litlblockdown2
		.LINKER2
			router-link(tag="LINKER2", to="/about") 參賽&助力
	.Block3
		.litlblockup3
		.litlblockdown3
		.LINKER3 助力規則
	.Block4
		.litlblockup4
		.litlblockdown4
		.LINKER4 報名參賽
	.Block5
		.litlblockup5
		.litlblockdown5
		.LINKER5 相關節目
	//- .columnbak
</template>

<style lang="sass">
.TOPSTUFF 
	font-family: Microsoft YaHei
	font-size: 28px
	color: rgb( 225, 225, 225)
	opacity: 100%
	z-index: 999
.TOPSTUFF:hover
	color: rgb( 255, 255, 255)

.LINKER1
	position: fixed
	z-index: 9999
	top: 2%
	cursor: pointer
	font-size: 30px
	letter-spacing: 40px
	left: 6%
	opacity: 70%

.LINKER2
	cursor: pointer
	position: fixed
	z-index: 9999
	top: 2.3%
	letter-spacing: 18px
	left: 23.5%
	opacity: 70%

.LINKER3
	position: fixed
	z-index: 9999
	top: 2.3%
	letter-spacing: 20px
	left: 44.5%
	opacity: 70%

.LINKER4
	position: fixed
	z-index: 9999
	top: 2.3%
	letter-spacing: 20px
	left: 64.5%
	opacity: 70%

.LINKER5
	position: fixed
	z-index: 9999
	top: 2.2%
	font-size: 29px
	letter-spacing: 20px
	left: 84.5%
	opacity: 70%
	
	
.Block1
	position: fixed
	z-index: 9999
	background: rgba( 255, 255, 255, 0)
	width: 20%
	height: 10%
	top: 0%
	left: 0%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.4s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.4s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.4s
.litlblockup
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255, 0.2)
	width: 20%
	height: 10%
	top: 0%
	left: 0%
	opacity: 0%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.4s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.4s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.4s
.litlblockdown
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255, 0.2)
	width: 20%
	height: 10%
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
.Block1:hover
	.litlblockdown
		opacity: 100%
		height: 3%
		top: 7%
	.litlblockup
		opacity: 100%
		height: 3%
	.LINKER1
		opacity: 100%

.Block2
	position: fixed
	z-index: 9999
	background: rgb( 255, 255, 255, 0)
	width: 20%
	height: 10%
	top: 0%
	left: 20%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.4s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.4s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.4s
.litlblockup2
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255, 0.2)
	width: 20%
	height: 10%
	top: 0%
	left: 20%
	opacity: 0%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.4s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.4s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.4s
.litlblockdown2
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255, 0.2)
	width: 20%
	// border: 1px solid red
	height: 10%
	top: 0%
	left: 20%
	opacity: 0%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.6s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.6s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.6s
.Block2:hover
	.litlblockdown2
		opacity: 100%
		height: 3%
		top: 7%
	.litlblockup2
		opacity: 100%
		height: 3%
	.LINKER2
		opacity: 100%

.Block3
	position: fixed
	z-index: 9999
	background: rgb( 255, 255, 255, 0)
	width: 20%
	height: 10%
	top: 0%
	left: 40%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.4s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.4s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.4s
.litlblockup3
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255, 0.2)
	width: 20%
	height: 10%
	top: 0%
	left: 40%
	opacity: 0%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.4s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.4s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.4s
.litlblockdown3
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255, 0.2)
	width: 20%
	height: 10%
	top: 0%
	left: 40%
	opacity: 0%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.6s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.6s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.6s
.Block3:hover
	.litlblockdown3
		opacity: 100%
		height: 3%
		top: 7%
	.litlblockup3
		opacity: 100%
		height: 3%
	.LINKER3
		opacity: 100%

.Block4
	position: fixed
	z-index: 999
	background: rgb( 255, 255, 255, 0)
	width: 20%
	height: 10%
	top: 0%
	left: 60%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.4s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.4s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.4s
.litlblockup4
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255, 0.2)
	width: 20%
	height: 10%
	top: 0%
	left: 60%
	opacity: 0%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.4s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.4s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.4s
.litlblockdown4
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255, 0.2)
	width: 20%
	height: 10%
	top: 0%
	left: 60%
	opacity: 0%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.6s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.6s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.6s
.Block4:hover
	.litlblockdown4
		opacity: 100%
		height: 3%
		top: 7%
	.litlblockup4
		opacity: 100%
		height: 3%
	.LINKER4
		opacity: 100%


.Block5
	position: fixed
	z-index: 999
	background: rgb( 255, 255, 255, 0)
	width: 20%
	height: 10%
	top: 0%
	left: 80%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.4s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.4s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.4s
.litlblockup5
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255, 0.2)
	width: 20%
	height: 10%
	top: 0%
	left: 80%
	opacity: 0%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.4s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.4s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.4s
.litlblockdown5
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255, 0.2)
	width: 20%
	height: 10%
	top: 0%
	left: 80%
	opacity: 0%
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.6s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.6s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.6s
.Block5:hover
	.litlblockdown5
		opacity: 100%
		height: 3%
		top: 7%
	.litlblockup5
		opacity: 100%
		height: 3%
	.LINKER5
		opacity: 100%

.colu1
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255)
	width: 0.2%
	height: 6%
	top: 2%
	left: 20%
	animation-name: downward
	animation-duration: 2s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.colu2
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255)
	width: 0.2%
	height: 6%
	top: 2%
	left: 40%
	animation-name: downward
	animation-duration: 2s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.colu3
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255)
	width: 0.2%
	height: 6%
	top: 2%
	left: 60%
	animation-name: downward
	animation-duration: 2s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.colu4
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255)
	width: 0.2%
	height: 6%
	top: 2%
	left: 80%
	animation-name: downward
	animation-duration: 2s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.colubutt
	position: fixed
	z-index: 1000
	background: rgb( 255, 255, 255)
	width: 100%
	height: 0.6%
	top: 10%
	left: 0%
	animation-name: downward
	animation-duration: 2s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.columnbak
	position: fixed
	z-index: 999
	background: rgba( 255, 255, 255, 0.3)
	width: 100%
	height: 10%
	top: 0%
	opacity: 10%
	left: 0%
	animation-name: downward
	animation-duration: 2s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 1s

.columnbak:hover
	opacity: 100%

// @keyframes nomove 
// 	0%
// 		left: 0%
// 		top: 0%
// 		width: 100%
// 		height: 100%	
// 		z-index: 90
// 	99%
// 		left: 0%
// 		top: 0%
// 		width: 100%
// 		height: 100%
// 		opacity: 100%
// 		z-index: 90
// 	100%
// 		z-index: -90
// 		left: 0%
// 		top: 0%
// 		width: 100%
// 		height: 100%
// 		opacity: 0%

// .backg1
// 	position: fixed
// 	z-index: -99
// 	left: 25%
// 	background: rgb( 0, 0, 0)
// 	animation-name: oxxo
// 	animation-duration: 3s
// 	animation-fill-mode: forwards
// 	animation-timing-function: ease-in-out

// .backg2
// 	position: fixed
// 	z-index: -98
// 	left: 0%
// 	background: rgb( 0, 0, 0)
// 	animation-name: oxxo1
// 	animation-delay: 1s
// 	animation-duration: 2s
// 	animation-fill-mode: forwards
// 	animation-timing-function: ease-in-out

// .backg3
// 	position: fixed
// 	z-index: -98
// 	left: 75%
// 	background: rgb( 0, 0, 0)
// 	animation-name: oxxo1
// 	animation-duration: 1.9s
// 	animation-delay: 1.1s
// 	animation-fill-mode: forwards
// 	animation-timing-function: ease-in-out

// @keyframes oxxo
// 	0%
// 		bottom: 110%
// 		height: 200%
// 		width: 50%
// 		z-index: 99
// 	20%
// 		bottom: -30%
// 		height: 200%
// 		width: 50%
// 		z-index: 99
// 	80%
// 		bottom: -30%
// 		height: 200%
// 		width: 50%
// 		opacity: 100%
// 		z-index: 99
// 	91%
// 		opacity: 0%
// 		bottom: -30%
// 		height: 200%
// 		width: 50%
// 		z-index: 99
// 	100%
// 		bottom: -30%
// 		height: 0%
// 		width: 50%
// 		opacity: 0%
// 		z-index: -99
// @keyframes oxxo1
// 	0%
// 		bottom: 110%
// 		height: 200%
// 		width: 75%
// 		z-index: 98
// 	20%
// 		z-index: 98
// 		bottom: -30%
// 		height: 200%
// 		width: 75%
// 	80%
// 		z-index: 98
// 		bottom: -30%
// 		height: 200%
// 		width: 75%
// 		opacity: 100%
	
// 	90%
// 		opacity: 0%
// 		z-index: 98
// 		bottom: -30%
// 		height: 200%
// 		width: 75%

// 	100%
// 		z-index: -98
// 		bottom: -30%
// 		height: 0%
// 		width: 75%
// 		opacity: 0%

</style>