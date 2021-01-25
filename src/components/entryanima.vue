<template lang="pug">
.anima
	.backg0
	.backg1
	.backg2
	.backg3
	.meteor1
	.meteor2
	.meteor3
	.taiL1
	.taiL2
	.taiL3
	.ground1
	.ground2
	.ground3

</template>

<style lang="sass">

.ground1
	position: absolute
	height: -0.2%
	width: -16%
	border-radius: -3px
	top: -75%
	left: -74%
	z-index: -99999
	background: white
	animation-name: ground1
	animation-delay: 2.2s
	animation-duration: 3.5s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.ground2
	position: absolute
	height: -9%
	width: -31%
	border-radius: 3px
	top: -66%
	left: -10%
	z-index: -99999
	background: white
	animation-name: ground2
	animation-delay: 2.2s
	animation-duration: 3.5s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.ground3
	position: absolute
	height: -22%
	width: -60%
	top: -21%
	border-radius: 3px
	left: -19.5%
	z-index: -99999
	background: white
	animation-name: ground3
	animation-delay: 2.2s
	animation-duration: 3.5s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out


.taiL2
	position: absolute
	z-index: -999
	background: white
	width: 0.2%
	height: 200%
	bottom: 157.5%
	left: 23.5%
	border-radius: 3px
	// border: 1px solid red
	animation-name: taiL
	animation-delay: 1.1s
	animation-duration: 2.4s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.taiL1
	position: absolute
	z-index: -999
	background: white
	width: 0.2%
	height: 200%
	bottom: 157.5%
	left: 81.2%
	border-radius: 3px
	// border: 1px solid red
	animation-name: taiL
	animation-delay: 1.1s
	animation-duration: 2.4s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.taiL3
	position: absolute
	z-index: -999
	background: white
	width: 0.2%
	height: 20%
	bottom: 157.5%
	left: 49.3%
	border-radius: 3px
	// border: 1px solid red
	animation-name: taiL2
	animation-delay: 1.1s
	animation-duration: 2.4s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.meteor3
	position: absolute
	z-index: 999
	background-image: url('https://upload.cc/i1/2021/01/25/rYJF2S.png')
	background-size: cover
	width: 3%
	height: 6%
	top: -40%
	left: 48%
	// border: 1px solid red
	animation-name: falling2
	animation-delay: 0.9s
	animation-duration: 2s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.meteor2
	position: fixed
	z-index: -999
	background-image: url('https://upload.cc/i1/2021/01/25/rYJF2S.png')
	background-size: cover
	width: 3%
	height: 6%
	top: -20%
	left: 80%
	// border: 1px solid red
	animation-name: falling
	animation-delay: 0.9s
	animation-duration: 2s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

	
.meteor1
	position: fixed
	z-index: -999
	background-image: url('https://upload.cc/i1/2021/01/25/rYJF2S.png')
	background-size: cover
	width: 3%
	height: 6%
	top: -20%
	left: 22%
	// border: 1px solid red
	animation-name: falling
	animation-delay: 0.9s
	animation-duration: 2s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

@keyframes ground2
	0%
		height: 0.2%
		width: 0%
		top: 75%
		left: 23.6%
		opacity: 100%
		z-index: 999999
	
	10%
		height: 0.2%
		left: 23.6%
		width: 0%
		top: 74%
		opacity: 100%
		z-index: 999999
	20%
		height: 0.2%
		left: 22.1%
		width: 3%
		top: 74%
		opacity: 100%
		z-index: 999999
	
	30%
		height: 0.2%
		left: 22.1%
		width: 3%
		top: 75%
		opacity: 100%
		z-index: 999999
	45%
		height: 0.2%
		width: 31%
		top: 75%
		left: 10%
		z-index: 999999
		opacity: 100%
	50%
		height: 0.2%
		width: 31%
		top: 75%
		left: 10%
		z-index: 999999
		opacity: 100%
	55%
		height: 9%
		width: 31%
		top: 66%
		left: 10%
		z-index: 99999
		opacity: 100%
	80%
		height: 9%
		width: 31%
		top: 66%
		opacity: 100%
		left: 10%
		z-index: 99999
	
	90%
		height: 0%
		width: 31%
		top: 66%
		opacity: 80%
		left: 10%
		z-index: 99999
	100%
		height: 0%
		width: 31%
		top: 66%
		left: 10%
		opacity: 0%
		z-index: -99999

@keyframes ground1
	0%
		height: 0.2%
		width: 0%
		top: 75%
		left: 81.5%
		opacity: 100%
		z-index: 999999
	
	10%
		height: 0.2%
		left: 81.5%
		width: 0%
		top: 74%
		opacity: 100%
		z-index: 999999
	20%
		height: 0.2%
		left: 80%
		width: 3%
		top: 74%
		opacity: 100%
		z-index: 999999
	
	30%
		height: 0.2%
		left: 80%
		width: 3%
		top: 75%
		opacity: 100%
		z-index: 999999
	45%
		height: 0.2%
		width: 16%
		top: 75%
		left: 74%
		z-index: 999999
		opacity: 100%
	50%
		height: 0.2%
		width: 16%
		top: 75%
		left: 74%
		z-index: 999999
		opacity: 100%
	55%
		height: 9%
		width: 16%
		top: 66%
		left: 74%
		z-index: 99999
		opacity: 100%
	80%
		height: 9%
		width: 16%
		top: 66%
		opacity: 100%
		left: 74%
		z-index: 99999
	
	90%
		height: 0%
		width: 16%
		top: 66%
		opacity: 80%
		left: 74%
		z-index: 99999
	100%
		height: 0%
		width: 16%
		top: 66%
		left: 74%
		opacity: 0%
		z-index: -99999

@keyframes ground3
	0%
		height: 0.22%
		width: 0%
		top: 43%
		left: 49.5%
		opacity: 100%
		z-index: 999999
	
	10%
		height: 0.22%
		left: 49.5%
		width: 0%
		top: 43%
		opacity: 100%
		z-index: 999999
	20%
		height: 0.22%
		left: 48%
		width: 3%
		top: 43%
		opacity: 100%
		z-index: 999999
	
	30%
		height: 0.22%
		left: 48%
		width: 3%
		top: 43%
		opacity: 100%
		z-index: 999999
	45%
		height: 0.22%
		width: 60%
		top: 43%
		left: 19.5%
		z-index: 999999
		opacity: 100%
	50%
		height: 0.2%
		width: 60%
		top: 43%
		left: 19.5%
		z-index: 999999
		opacity: 100%
	55%
		height: 22%
		width: 60%
		top: 21%
		left: 19.5%
		z-index: 99999
		opacity: 100%
	80%
		height: 22%
		width: 60%
		top: 21%
		opacity: 100%
		left: 19.5%
		z-index: 99999
	
	90%
		height: 0%
		width: 60%
		top: 21%
		opacity: 80%
		left: 19.5%
		z-index: 99999
	100%
		height: 0%
		width: 60%
		top: 21%
		left: 19.5%
		opacity: 0%
		z-index: -99999

@keyframes taiL
	0%
		width: 0.2%
		height: 200%
		bottom: 210%
		opacity: 100%
		z-index: 999999
	
	75%
		width: 0.2%
		height: 200%
		bottom: 30%
		opacity: 100%
		z-index: 999999
	80%
		width: 0.2%
		height: 200%
		bottom: 30%
		opacity: 100%
		z-index: 999999
	95%
		opacity: 100%
	100%
		width: 0.1%
		height: 1%
		bottom: 25%
		opacity: 0%
		z-index: 999999

@keyframes taiL2
	0%
		width: 0.2%
		height: 200%
		bottom: 230%
		opacity: 100%
		z-index: 999999
	
	75%
		width: 0.2%
		height: 200%
		bottom: 62%
		opacity: 100%
		z-index: 999999
	80%
		width: 0.2%
		height: 200%
		bottom: 62%
		opacity: 100%
		z-index: 999999
	95%
		opacity: 100%
	100%
		width: 0.1%
		height: 1%
		bottom: 57%
		opacity: 0%
		z-index: 999999

@keyframes falling2
	0%
		top: -130%
		height: 2%
		width: 1%
		opacity: 100%
		z-index: 999999
	90%
		height: 6%
		width: 3%
		opacity: 100%
		top: 36%
		z-index: 999999
	100%
		top: 40%
		height: 1%
		width: 3%
		opacity: 1%
		z-index: -99


@keyframes falling
	0%
		top: -110%
		height: 2%
		width: 1%
		opacity: 100%
		z-index: 999999
	90%
		height: 6%
		width: 3%
		opacity: 100%
		top: 64%
		z-index: 999999
	100%
		top: 70%
		height: 1%
		width: 3%
		opacity: 1%
		z-index: -99

.backg0
	position: fixed
	z-index: -90
	background: rgb( 255, 255, 255)
	animation-name: nomove
	animation-duration: 2s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

@keyframes nomove 
	0%
		left: 0%
		top: 0%
		width: 100%
		height: 100%	
		z-index: 9999
	99%
		left: 0%
		top: 0%
		width: 100%
		height: 100%
		opacity: 100%
		z-index: 9999
	100%
		z-index: -90
		left: 0%
		top: 0%
		width: 100%
		height: 100%
		opacity: 0%

.backg1
	position: fixed
	z-index: -99
	left: 25%
	background: rgb( 0, 0, 0)
	animation-name: oxxo
	animation-duration: 5.3s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.backg2
	position: fixed
	z-index: -98
	left: 0%
	background: rgb( 0, 0, 0)
	animation-name: oxxo1
	animation-delay: 0.7s
	animation-duration: 4.3s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.backg3
	position: fixed
	z-index: -98
	left: 75%
	background: rgb( 0, 0, 0)
	animation-name: oxxo1
	animation-duration: 4.2s
	animation-delay: 0.8s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

@keyframes oxxo
	0%
		bottom: 110%
		height: 200%
		width: 50%
		z-index: 99999
	15%
		bottom: -30%
		height: 200%
		width: 50%
		z-index: 99999
	80%
		bottom: -30%
		height: 200%
		width: 50%
		opacity: 100%
		z-index: 99999
	91%
		opacity: 0%
		bottom: -30%
		height: 200%
		width: 50%
		z-index: 99999
	100%
		bottom: -30%
		height: 0%
		width: 50%
		opacity: 0%
		z-index: -99

@keyframes oxxo1
	0%
		bottom: 110%
		height: 200%
		width: 75%
		z-index: 99999
	15%
		z-index: 99999
		bottom: -30%
		height: 200%
		width: 75%
	80%
		z-index: 99999
		bottom: -30%
		height: 200%
		width: 75%
		opacity: 100%
	
	90%
		opacity: 0%
		z-index: 99999
		bottom: -30%
		height: 200%
		width: 75%

	100%
		z-index: -98
		bottom: -30%
		height: 0%
		width: 75%
		opacity: 0%

</style>