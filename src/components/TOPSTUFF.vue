<template lang="pug">
//- .toptop
//- 	.topformat
//- 		.topbottons


//- 	//- el-dropdown.topformat(v-for="item in list")
//- 	//- 	span.topbottons.el-dropdown-link {{item.title}}
//- 	//- 	//- i.el-icon-arrow-down.el-icon--right
//- 	//- 	el-dropdown-menu(slot="dropdown")
//- 	//- 		el-dropdown-item.dropdown(v-for="option in item.secondtitle") {{option}}
//- 	el-menu.topformat.el-menu-demo(:default-active="activeIndex" mode="horizontal" @select="handleSelect" v-for="item in list" background-color="#caf0f8")
//- 		el-submenu(index="2")
//- 			template.topbottons(slot="title") {{item.title}}
//- 			el-menu-item.dropdown(index="2-1")(v-for="option in item.secondtitle") {{option}}

el-menu(
    :default-active="activeIndex",
    menu-trigger="hover",
    mode="horizontal",
    @select="handleSelect",
    text-color= "#1d3557",
    background-color="rgba(255,255,255,0.2)",
    letter-spacing="10%"
) 
	.toptop0
		el-submenu.toptop(index="4", menu-trigger="hover")
			template.nthuipta(slot="title") 招生資訊
			el-menu-item.nthuipta(index="4-1") 春之清華卓越獎五名
			el-menu-item.nthuipta(index="4-2") 學士班臉書粉絲頁
			el-submenu.nthuipta(index="4-3", menu-trigger="hover") 
				template.nthuipta(slot="title") ２０２０招生資訊
				el-menu-item(index="4-3-1") ２０２０錄取名單	
				el-menu-item(index="4-3-2") ２０２０招生簡章
				el-menu-item(index="4-3-3") ２０２０個人申請第二階段甄選注意事項
				el-menu-item(index="4-3-3") ２０２０報名繳交資料
				el-menu-item.nthuipta(index="4-4") 招生Ｑ＆Ａ
			el-submenu.nthuipta(index="4-5", menu-trigger="hover") 
				template(slot="title") 過往招生資訊
				el-submenu.nthuipta(index="4-5-1", menu-trigger="hover") 
					template.nthuipta(slot="title") ２０１９年招生資訊
					el-menu-item(index="4-5-1-1") ２０１９錄取名單
					el-menu-item(index="4-5-1-2") ２０１９招生簡章
					el-menu-item(index="4-5-1-3") ２０１９個人申請第二階段甄選注意事項
					el-menu-item(index="4-5-1-4") ２０１９報名繳交資料
				el-submenu.nthuipta(index="4-5-2", menu-trigger="hover") 
					template.nthuipta(slot="title") ２０１８年招生資訊
					el-menu-item(index="4-5-2-1") ２０１８錄取名單
					el-menu-item(index="4-5-2-2") ２０１８招生簡章
					el-menu-item(index="4-5-2-3") ２０１８個人申請第二階段甄選注意事項
					el-menu-item(index="4-5-2-4") ２０１８報名繳交資料
		el-submenu.toptop1(index="5", menu-trigger="hover") 
			template.nthuipta(slot="title") 學士班
			el-menu-item.nthuipta(index="5-1") 學士班簡介
			el-menu-item.nthuipta(index="5-2") 學士班課程
			el-menu-item.nthuipta(index="5-3") 國際交換
			el-menu-item.nthuipta(index="5-4") 藝術學院大樓(New)
		el-submenu.toptop2(index="6", menu-trigger="hover") 
			template.nthuipta(slot="title") 師資
			el-menu-item.nthuipta(index="6-1") 學士班師資
			el-menu-item.nthuipta(index="6-2") 藝設系師資
			el-menu-item.nthuipta(index="6-3") 音樂系師資
			el-menu-item.nthuipta(index="6-4") 電資學院師資
		el-submenu.toptop3(index="7", menu-trigger="hover") 
			template.nthuipta(slot="title") 科藝賞析
			el-menu-item.nthuipta(index="7-1") 數位文創作品
			el-menu-item.nthuipta(index="7-2") 互動藝術作品
			el-menu-item.nthuipta(index="7-3") 動力藝術作品
			el-menu-item.nthuipta(index="7-4") 聲音藝術作品
			el-menu-item.nthuipta(index="7-4") 科技表演藝術
//-   .header
//-     .rect
//-     .circle.circle1 核心能力
//-     .circle.circle2 學士班特色
//-     .header_word
//-       .header_word1 國立清華大學
//-       .header_word2 藝術學院學士班
//-   .news
//-     .news_rect_word 最新消息
//-     .news_flex
//-       .news_item(v-for="item in newsList")
//-         .news_img(:style="{ backgroundImage: 'url(' + item.img + ')' }")
//-         .news_text {{ item.text }}
//-   .works
//-     .works_rect_word 優秀作品
//-     .works_flex
//-       .works_item(v-for="item in worksList")
//-         .works_img(:style="{ backgroundImage: 'url(' + item.img + ')' }")
//-         .works_text {{ item.text }}
//-   .scho
//-     .scho_rect_word 最酷的系，要的是最酷的你！
//-     .scho_rect
//-       .scho_img
//-   router-view
</template>


<script>
// export default {
// 	name: 'Contact',
// 	props: {
// 		msg: String
// 	},
// 	data(){
// 		return{
// 			list:[
// 				{title:'招生'},
// 				{title:'學士班'},
// 				{title:'師資'},
// 				{title:'科藝賞析'},
// 			]
// 		}
// 	}
// }
</script>

<style lang="sass">
.toptop0
	display: flex
	flex-direction: row
	//border: 1px solid red
	justify-content: space-between
	position: fixed
	width: 100%
	height: 8%
	top: 0px
	z-index: 1 
	background-color: #caf0f8
	opacity: 30%
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 0.5s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 0.5s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 0.5s

.toptop
	display: flex
	flex-direction: row
	//border: 1px solid red
	justify-content: space-between
	position: fixed
	left: 10%
	top: 0%
	z-index: 100
	background-color: #caf0f8
	opacity: 10%
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 0.5s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 0.5s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 0.5s
	color: rgba(0, 0, 0, 1)

.toptop1
	display: flex
	flex-direction: row
	//border: 1px solid red
	justify-content: space-between
	position: fixed
	top: 0%
	left: 35%
	z-index: 100
	background-color: #caf0f8
	opacity: 10%
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.toptop2
	display: flex
	flex-direction: row
	//border: 1px solid red
	justify-content: space-between
	position: fixed
	top: 0%
	left: 60%
	z-index: 100
	background-color: #caf0f8
	opacity: 10%
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.toptop3
	display: flex
	flex-direction: row
	//border: 1px solid red
	justify-content: space-between
	position: fixed
	top: 0%
	left: 85%
	z-index: 100
	background-color: #caf0f8
	opacity: 10%
	transition-property: opacity, width ,height,left,font-size,color,z-index,top
	transition-duration: 1s
	transition-timing-function: ease-out
	-webkit-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-webkit-transition-duration: 1s
	-o-transition-property: opacity, width ,height,left,font-size,color,z-index,top
	-o-transition-duration: 1s

.topformat
	//border: 1px solid blue
	width: 1340px
	height: 45px
	display: flex
	flex-direction: row

.toptop0:hover 
	opacity: 90%
	.toptop
		opacity: 70%
	.toptop1
		opacity: 70%
	.toptop2
		opacity: 70%
	.toptop3
		opacity: 70%
.toptop:hover
	opacity: 100%
.toptop1:hover
	opacity: 100%
.toptop2:hover
	opacity: 100%
.toptop:hover
	opacity: 100%

.nthuipta:hover
	opacity: 100%
// .topbottons
// 	cursor: pointer
// 	//border: 1px solid orange
// 	width: fit-content
// 	height: 40px
// 	position: relative
// 	top: 35px
// 	left: 50%
// 	font-style: normal
// 	font-weight: normal
// 	font-size: 30px
// 	//background-color: #ade8f4
// 	//line-height: 95px
// 	color: white
// .dropdown


</style>