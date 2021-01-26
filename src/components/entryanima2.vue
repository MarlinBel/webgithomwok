<template lang="pug">
.animaa
	.backg00
	.backg11
	.backg22
	.backg33
	//- .meteor1
	//- .meteor2
	//- .meteor3
	//- .taiL1
	//- .taiL2
	//- .taiL3
	//- .ground1
	//- .ground2
	//- .ground3

</template>

<style lang="sass">

.backg00
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

.backg11
	position: fixed
	z-index: -99
	left: 25%
	background: rgb( 0, 0, 0)
	animation-name: oxxo
	animation-duration: 2.2s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.backg22
	position: fixed
	z-index: -98
	left: 0%
	background: rgb( 0, 0, 0)
	animation-name: oxxo1
	animation-delay: 0.9s
	animation-duration: 1.3s
	animation-fill-mode: forwards
	animation-timing-function: ease-in-out

.backg33
	position: fixed
	z-index: -98
	left: 75%
	background: rgb( 0, 0, 0)
	animation-name: oxxo1
	animation-duration: 1.2s
	animation-delay: 1s
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