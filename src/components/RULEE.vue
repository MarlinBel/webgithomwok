<template lang="pug">

.RULEE
	.ruleopen
	.ruletitle 助力規則
	.rulecon 第一與第二階段助力（第一期至第七期）：<br>

				<br>登陸帳號，普通用戶每天擁有一次助力機會，<br>每次可為9位訓練生助力，不可重複選擇同一訓練生。<br>
				<br>VIP用戶每天額外擁有一次助力機會，<br>每次可為9位訓練生助力，不可重複選擇同一訓練生。<br>
				<br>打開APP，進入助力通道，每天額外擁有一次助力機會。<br>每次可為9位訓練生助力，不可重複選擇同一訓練生。<br>
				<br>加入官方唯一助力小程序——真果粒大叔福利社，<br>獲得更多助力機會，支持公益活動。<br><br><br>
				<br>第三階段助力（第八期至第九期）：<br>

				<br>登陸帳號，普通用戶每天擁有一次助力機會，<br>每次可為2位訓練生助力，不可重複選擇同一訓練生。<br>
				<br>VIP用戶每天額外擁有一次助力機會，<br>每次可為2位訓練生助力，不可重複選擇同一訓練生。<br>
				<br>打開APP，進入助力通道，<br>每天額外擁有一次助力機會。<br>每次可為2位訓練生助力，不可重複選擇同一訓練生。<br>
				<br>加入官方唯一助力小程序——真果粒大叔福利社，<br>獲得更多助力機會，支持公益活動。<br><br><br>
				<br>第四階段助力（第十期至第十二期）：<br>

				<br>登陸帳號，普通用戶每天擁有一次助力機會，<br>每次可為1位訓練生助力。<br>
				<br>VIP用戶每天額外擁有一次助力機會，<br>每次可為1位訓練生助力。<br>
				<br>打開APP，進入助力通道，每天額外擁有一次助力機會。<br>每次可為1位訓練生助力。<br>
				<br>加入官方唯一助力小程序——真果粒大叔福利社，<br>獲得更多助力機會，支持公益活動。
	.ruleclose 收起 <br>規則 
	.rulenow 現在是第一期，助力時間為<br>上午8:00至下午17:00<br>規則都瞭解了嗎?開始助力吧!
	.helplink >>開始助力
		.litleboxup
		.litleboxdown
		.LINKA

</template>

<style lang="sass">
.RULEE
	font-family: Microsoft YaHei

.ruleopen
	position: absolute
	top: 35%
	left: 0%
	width: 100%
	height: 30%
	// border: 1px solid red
	z-index: 71
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.6s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.6s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.6s

.ruleopen:hover~.rulecon
	font-size: 20px
	opacity: 100%
	height: 200%
	top: 60%
	left: 0%
	width: 100%
	// border: 1px solid red

.ruleopen:hover~.ruleclose
	position: fixed
	font-size: 48px
	border: 1px solid rgb( 210, 210, 210)
	right: 0%
	width: 7%
	height: 16%
	top: 75%
	z-index: 75
	color: rgb( 210, 210, 210)

.ruleopen:hover~.helplink
	cursor: pointer
	position: absolute
	font-size: 52px
	top: 265%
	left: 35%
	letter-spacing: 30px
	color: rgb( 210, 210, 210)
	z-index: 70	

.ruleopen:hover~.rulenow
	position: absolute
	font-size: 40px
	top: 236%
	width: 60%
	left: 22%
	letter-spacing: 30px
	color: rgb( 210, 210, 210)
	z-index: 70	

.ruleclose
	position: fixed
	font-size: 0px
	// border: 1px solid rgb( 210, 210, 210)
	right: 0%
	width: 0%
	height: 0%
	top: 75%
	z-index: 75
	color: rgb( 210, 210, 210)
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.6s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.6s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.6s

.ruletitle
	position: absolute
	font-size: 80px
	top: 35%
	left: 34%
	letter-spacing: 60px
	color: rgb( 210, 210, 210)
	z-index: 70
	// border: 1px solid red

.rulecon
	position: absolute
	font-size: 0px
	width: 0%
	top: 50%
	height: 0%
	opacity: 0%
	left: 50%
	letter-spacing: 10px
	color: rgb( 210, 210, 210)
	z-index: 70
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.6s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.6s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.6s
	
.rulecon:hover
	font-size: 20px
	opacity: 100%
	height: 200%
	top: 60%
	left: 0%
	width: 100%
	// border: 1px solid red

.rulecon:hover~.ruleclose
	position: fixed
	font-size: 48px
	border: 1px solid rgb( 210, 210, 210)
	right: 0%
	width: 7%
	height: 16%
	top: 75%
	z-index: 75
	color: rgb( 210, 210, 210)

.rulecon:hover~.helplink
	cursor: pointer
	position: absolute
	font-size: 52px
	top: 265%
	left: 35%
	letter-spacing: 30px
	color: rgb( 210, 210, 210)
	z-index: 70	

.rulecon:hover~.rulenow
	position: absolute
	font-size: 40px
	top: 236%
	width: 60%
	left: 22%
	letter-spacing: 30px
	color: rgb( 210, 210, 210)
	z-index: 70	

// .helplink
// 	cursor: pointer
// 	position: absolute
// 	font-size: 52px
// 	top: 80%
// 	left: 35%
// 	letter-spacing: 30px
// 	color: rgb( 210, 210, 210)
// 	z-index: 70	
// 	transition-property: opacity, width ,height,left,font-size,color,top,z-index
// 	transition-duration: 1s
// 	transition-timing-function: ease-out
// 	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
// 	-webkit-transition-duration: 1s
// 	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
// 	-o-transition-duration: 1s

.helplink
	cursor: pointer
	position: absolute
	font-size: 52px
	top: 80%
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
.litleboxup
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
.litleboxdown
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

.helplink:hover
	.litleboxdown
		opacity: 80%
		height: 10%
		top: 90%
		// border: 1px solid red
	.litleboxup
		opacity: 80%
		height: 10%
		top: 0%
		// border: 1px solid red

.rulenow
	position: absolute
	font-size: 35px
	top: 60%
	width: 60%
	left: 22%
	letter-spacing: 30px
	color: rgb( 210, 210, 210)
	z-index: 70	
	transition-property: opacity, width ,height,left,font-size,color,top,z-index
	transition-duration: 0.6s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-webkit-transition-duration: 0.6s
	-o-transition-property: opacity, width ,height,left,font-size,color,top,z-index
	-o-transition-duration: 0.6s

</style>