<template>
	<view class="container container22243">
		<view class="flex diygw-col-24 flex-direction-column flex-nowrap flex-clz">
			<view class="flex diygw-col-24 items-center flex-nowrap flex2-clz">
				<view class="diy-icon-location diygw-col-0 text1-clz"> </view>
				<view class="diygw-col-0 text-clz diygw-text-md"> 广州市华南师范大学城区 </view>
				<view class="diy-icon-triangledownfill diygw-col-0 text2-clz"> </view>
			</view>
			<view class="diygw-col-24 white search-clz">
				<view class="diygw-search">
					<view class="flex1 align-center flex padding-xs radius">
						<text style="color: #555 !important" class="diy-icon-search"></text>
						<input class="flex1" name="search" type="" v-model="search" placeholder="请输入店铺名或商品店" />
					</view>
				</view>
			</view>
		</view>
		<view class="flex flex-wrap diygw-col-24 flex-direction-column flex10-clz">
			<view class="flex diygw-col-24">
				<swiper class="swiper" indicator-color="rgba(51, 51, 51, 0.39)" indicator-active-color="#fff" indicator-dots="true" autoplay interval="3000" circular="true" style="height: 160px">
					<swiper-item class="diygw-swiper-item">
						<view class="diygw-swiper-item-wrap">
							<image src="/static/11.png" class="diygw-swiper-image"></image>
						</view>
					</swiper-item>
					<swiper-item class="diygw-swiper-item">
						<view class="diygw-swiper-item-wrap">
							<image src="/static/123.png" class="diygw-swiper-image"></image>
						</view>
					</swiper-item>
					<swiper-item class="diygw-swiper-item">
						<view class="diygw-swiper-item-wrap">
							<image src="/static/wbt-14.png" class="diygw-swiper-image"></image>
						</view>
					</swiper-item>
				</swiper>
			</view>
			<view class="flex diygw-col-24">
				<diy-noticebar class="flex1 diy-notice-bar" color="#07c160" bgColor="#fff" leftIcon="diy-icon-notification">
					<block v-slot:content>
						<text class="diy-notice-item"> DIY官网做好的拖拽式可视化设计工具 </text>
					</block>
				</diy-noticebar>
			</view>
		</view>
		<view class="flex diygw-col-24 items-start flex-nowrap flex1-clz">
			<image src="/static/3b1dbd90dc1b852198e974e49dcdc353.png" class="image-size diygw-image diygw-col-0 image-clz" mode="widthFix"></image>
			<view class="flex flex-wrap diygw-col-0 flex-direction-column flex3-clz">
				<view class="diygw-col-24 diygw-text-md"> 重庆小面（华师北） </view>
				<view class="flex flex-wrap diygw-col-24 justify-between items-center flex6-clz">
					<view class="flex diygw-col-0 flex-nowrap flex4-clz">
						<view class="diy-icon-starfill diygw-col-0 text4-clz"> 5分 </view>
						<view class="diygw-col-0 text5-clz"> 月售999份 </view>
					</view>
					<view class="diygw-col-0 text9-clz"> 营业中 </view>
				</view>
				<view class="flex diygw-col-24 flex-nowrap flex5-clz">
					<view class="diygw-col-0 text7-clz"> 重庆小面 </view>
					<view class="diygw-col-0 text8-clz"> 梅菜扣肉饭 </view>
				</view>
			</view>
		</view>
		<view class="flex diygw-col-24 items-start flex-nowrap flex8-clz">
			<image src="/static/100.png" class="image3-size diygw-image diygw-col-0 image3-clz" mode="widthFix"></image>
			<view class="flex flex-wrap diygw-col-0 flex-direction-column flex12-clz">
				<view class="diygw-col-24 diygw-text-md"> 千里香混沌王（华师北） </view>
				<view class="flex flex-wrap diygw-col-24 justify-between items-center flex16-clz">
					<view class="flex diygw-col-0 flex-nowrap flex18-clz">
						<view class="diy-icon-starfill diygw-col-0 text15-clz"> 5分 </view>
						<view class="diygw-col-0 text19-clz"> 月售999份 </view>
					</view>
					<view class="diygw-col-0 text22-clz"> 营业中 </view>
				</view>
				<view class="flex diygw-col-24 flex-nowrap flex20-clz">
					<view class="diygw-col-0 text24-clz"> 小混沌 </view>
					<view class="diygw-col-0 text26-clz"> 排骨面（粉） </view>
				</view>
			</view>
		</view>
		<view class="flex diygw-col-24 items-start flex-nowrap flex7-clz">
			<image src="/static/3b1dbd90dc1b852198e974e49dcdc353.png" class="image2-size diygw-image diygw-col-0 image2-clz" mode="widthFix"></image>
			<view class="flex flex-wrap diygw-col-0 flex-direction-column flex9-clz">
				<view class="diygw-col-24 diygw-text-md"> 渔夫酸菜鱼（华师北） </view>
				<view class="flex flex-wrap diygw-col-24 justify-between items-center flex11-clz">
					<view class="flex diygw-col-0 flex-nowrap flex13-clz">
						<view class="diy-icon-starfill diygw-col-0 text12-clz"> 5分 </view>
						<view class="diygw-col-0 text14-clz"> 月售999份 </view>
					</view>
					<view class="diygw-col-0 text16-clz"> 营业中 </view>
				</view>
				<view class="flex diygw-col-24 flex-nowrap flex15-clz">
					<view class="diygw-col-0 text18-clz"> 无骨酸菜鱼 </view>
					<view class="diygw-col-0 text20-clz"> 水煮牛肉 </view>
					<view class="diygw-col-0 text6-clz"> 番茄肥牛 </view>
				</view>
			</view>
		</view>
		<view class="version text-grey flex-direction-column flex diygw-col-24 justify-center align-center">
			<view> DIY官网代码生成器生成 </view>
			<view> http://www.diygw.com </view>
		</view>
		<view class="clearfix"></view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				//用户全局信息
				userInfo: {},
				//页面传参
				globalOption: {},
				//自定义全局变量
				globalData: {},
				search: ''
			};
		},
		onShow() {
			this.setCurrentPage(this);
		},
		onLoad(option) {
			this.setCurrentPage(this);
			if (option) {
				this.setData({
					globalOption: this.getOption(option)
				});
			}

			this.init();
		},
		methods: {
			async init() {}
		}
	};
</script>

<style lang="scss" scoped>
	.flex-clz {
		z-index: 100;
		background-repeat: no-repeat;
		background-size: cover;
		background-image: url(/static/cytb.png);
		background-position: bottom center;
		height: 100px;
	}
	.flex2-clz {
		background-color: #17b28a;
		z-index: 100;
		color: #ffffff;
	}
	.text1-clz {
		margin-left: 10px;
		font-size: 18px !important;
		margin-top: 0px;
		margin-bottom: 0px;
		margin-right: 0px;
	}
	.text-clz {
		margin-left: 5px;
		margin-top: 5px;
		margin-bottom: 5px;
		margin-right: 5px;
	}
	.text2-clz {
		font-size: 18px !important;
	}
	.search-clz {
		margin-left: 10px;
		border-bottom-left-radius: 50px;
		box-shadow: 0px 2px 3px rgba(23, 178, 138, 0.65);
		overflow: hidden;
		width: calc(100% - 10px - 10px) !important;
		border-top-left-radius: 50px;
		margin-top: 10px;
		border-top-right-radius: 50px;
		border-bottom-right-radius: 50px;
		margin-bottom: 10px;
		margin-right: 10px;
	}
	.flex10-clz {
		margin-left: 10px;
		border-bottom-left-radius: 10px;
		box-shadow: 1px 1px 3px 1px rgba(154, 154, 154, 0.37);
		z-index: 100;
		overflow: hidden;
		width: calc(100% - 10px - 10px) !important;
		border-top-left-radius: 10px;
		margin-top: 0px;
		border-top-right-radius: 10px;
		border-bottom-right-radius: 10px;
		margin-bottom: 10px;
		margin-right: 10px;
	}
	.flex1-clz {
		padding-top: 10px;
		border-bottom-left-radius: 10px;
		z-index: 100;
		padding-left: 10px;
		padding-bottom: 10px;
		border-top-right-radius: 10px;
		margin-right: 10px;
		margin-left: 10px;
		box-shadow: 1px 1px 3px 1px rgba(154, 154, 154, 0.37);
		overflow: hidden;
		width: calc(100% - 10px - 10px) !important;
		border-top-left-radius: 10px;
		margin-top: 10px;
		border-bottom-right-radius: 10px;
		margin-bottom: 10px;
		padding-right: 10px;
	}
	.image-clz {
		border-bottom-left-radius: 6px;
		overflow: hidden;
		border-top-left-radius: 6px;
		border-top-right-radius: 6px;
		border-bottom-right-radius: 6px;
	}
	.image-size {
		height: 100px !important;
		width: 100px !important;
	}
	.flex3-clz {
		padding-top: 0px;
		z-index: 100;
		flex: 1;
		padding-left: 5px;
		padding-bottom: 0px;
		height: 100px;
		padding-right: 0px;
	}
	.flex6-clz {
		z-index: 100;
		flex: 1;
	}
	.flex4-clz {
		z-index: 100;
	}
	.text4-clz {
		margin-left: 0px;
		color: #ff9e01;
		margin-top: 5px;
		margin-bottom: 5px;
		margin-right: 5px;
	}
	.text5-clz {
		margin-left: 5px;
		margin-top: 5px;
		margin-bottom: 5px;
		margin-right: 5px;
	}
	.text9-clz {
		border: 1px solid #17b28a;
		padding-top: 5px;
		border-bottom-left-radius: 20px;
		color: #17b28a;
		padding-left: 10px;
		padding-bottom: 5px;
		border-top-right-radius: 20px;
		margin-right: 5px;
		margin-left: 0px;
		overflow: hidden;
		border-top-left-radius: 20px;
		margin-top: 5px;
		border-bottom-right-radius: 20px;
		margin-bottom: 5px;
		padding-right: 10px;
	}
	.flex5-clz {
		z-index: 100;
	}
	.text7-clz {
		border: 1px solid #0ba1f7;
		padding-top: 3px;
		border-bottom-left-radius: 3px;
		color: #0ba1f7;
		padding-left: 5px;
		padding-bottom: 3px;
		border-top-right-radius: 3px;
		margin-right: 5px;
		margin-left: 0px;
		overflow: hidden;
		border-top-left-radius: 3px;
		margin-top: 0px;
		border-bottom-right-radius: 3px;
		margin-bottom: 0px;
		padding-right: 5px;
	}
	.text8-clz {
		border: 1px solid #0ba1f7;
		padding-top: 3px;
		border-bottom-left-radius: 3px;
		color: #0ba1f7;
		padding-left: 5px;
		padding-bottom: 3px;
		border-top-right-radius: 3px;
		margin-right: 5px;
		margin-left: 0px;
		overflow: hidden;
		border-top-left-radius: 3px;
		margin-top: 0px;
		border-bottom-right-radius: 3px;
		margin-bottom: 0px;
		padding-right: 5px;
	}
	.flex8-clz {
		padding-top: 10px;
		border-bottom-left-radius: 10px;
		z-index: 100;
		padding-left: 10px;
		padding-bottom: 10px;
		border-top-right-radius: 10px;
		margin-right: 10px;
		margin-left: 10px;
		box-shadow: 1px 1px 3px 1px rgba(154, 154, 154, 0.37);
		overflow: hidden;
		width: calc(100% - 10px - 10px) !important;
		border-top-left-radius: 10px;
		margin-top: 10px;
		border-bottom-right-radius: 10px;
		margin-bottom: 10px;
		padding-right: 10px;
	}
	.image3-clz {
		border-bottom-left-radius: 6px;
		overflow: hidden;
		border-top-left-radius: 6px;
		border-top-right-radius: 6px;
		border-bottom-right-radius: 6px;
	}
	.image3-size {
		height: 100px !important;
		width: 100px !important;
	}
	.flex12-clz {
		padding-top: 0px;
		z-index: 100;
		flex: 1;
		padding-left: 5px;
		padding-bottom: 0px;
		height: 100px;
		padding-right: 0px;
	}
	.flex16-clz {
		z-index: 100;
		flex: 1;
	}
	.flex18-clz {
		z-index: 100;
	}
	.text15-clz {
		margin-left: 0px;
		color: #ff9e01;
		margin-top: 5px;
		margin-bottom: 5px;
		margin-right: 5px;
	}
	.text19-clz {
		margin-left: 5px;
		margin-top: 5px;
		margin-bottom: 5px;
		margin-right: 5px;
	}
	.text22-clz {
		border: 1px solid #17b28a;
		padding-top: 5px;
		border-bottom-left-radius: 20px;
		color: #17b28a;
		padding-left: 10px;
		padding-bottom: 5px;
		border-top-right-radius: 20px;
		margin-right: 5px;
		margin-left: 0px;
		overflow: hidden;
		border-top-left-radius: 20px;
		margin-top: 5px;
		border-bottom-right-radius: 20px;
		margin-bottom: 5px;
		padding-right: 10px;
	}
	.flex20-clz {
		z-index: 100;
	}
	.text24-clz {
		border: 1px solid #0ba1f7;
		padding-top: 5px;
		border-bottom-left-radius: 3px;
		color: #0ba1f7;
		padding-left: 5px;
		padding-bottom: 5px;
		border-top-right-radius: 3px;
		margin-right: 5px;
		margin-left: 0px;
		overflow: hidden;
		border-top-left-radius: 3px;
		margin-top: 0px;
		border-bottom-right-radius: 3px;
		margin-bottom: 0px;
		padding-right: 5px;
	}
	.text26-clz {
		border: 1px solid #0ba1f7;
		padding-top: 5px;
		border-bottom-left-radius: 3px;
		color: #0ba1f7;
		padding-left: 5px;
		padding-bottom: 5px;
		border-top-right-radius: 3px;
		margin-right: 5px;
		margin-left: 0px;
		overflow: hidden;
		border-top-left-radius: 3px;
		margin-top: 0px;
		border-bottom-right-radius: 3px;
		margin-bottom: 0px;
		padding-right: 5px;
	}
	.flex7-clz {
		padding-top: 10px;
		border-bottom-left-radius: 10px;
		z-index: 100;
		padding-left: 10px;
		padding-bottom: 10px;
		border-top-right-radius: 10px;
		margin-right: 10px;
		margin-left: 10px;
		box-shadow: 1px 1px 3px 1px rgba(154, 154, 154, 0.37);
		overflow: hidden;
		width: calc(100% - 10px - 10px) !important;
		border-top-left-radius: 10px;
		margin-top: 10px;
		border-bottom-right-radius: 10px;
		margin-bottom: 10px;
		padding-right: 10px;
	}
	.image2-clz {
		border-bottom-left-radius: 6px;
		overflow: hidden;
		border-top-left-radius: 6px;
		border-top-right-radius: 6px;
		border-bottom-right-radius: 6px;
	}
	.image2-size {
		height: 100px !important;
		width: 100px !important;
	}
	.flex9-clz {
		padding-top: 0px;
		z-index: 100;
		flex: 1;
		padding-left: 5px;
		padding-bottom: 0px;
		height: 100px;
		padding-right: 0px;
	}
	.flex11-clz {
		z-index: 100;
		flex: 1;
	}
	.flex13-clz {
		z-index: 100;
	}
	.text12-clz {
		margin-left: 0px;
		color: #ff9e01;
		margin-top: 5px;
		margin-bottom: 5px;
		margin-right: 5px;
	}
	.text14-clz {
		margin-left: 5px;
		margin-top: 5px;
		margin-bottom: 5px;
		margin-right: 5px;
	}
	.text16-clz {
		border: 1px solid #17b28a;
		padding-top: 5px;
		border-bottom-left-radius: 20px;
		color: #17b28a;
		padding-left: 10px;
		padding-bottom: 5px;
		border-top-right-radius: 20px;
		margin-right: 5px;
		margin-left: 0px;
		overflow: hidden;
		border-top-left-radius: 20px;
		margin-top: 5px;
		border-bottom-right-radius: 20px;
		margin-bottom: 5px;
		padding-right: 10px;
	}
	.flex15-clz {
		z-index: 100;
	}
	.text18-clz {
		border: 1px solid #0ba1f7;
		padding-top: 5px;
		border-bottom-left-radius: 3px;
		color: #0ba1f7;
		padding-left: 5px;
		padding-bottom: 5px;
		border-top-right-radius: 3px;
		margin-right: 5px;
		margin-left: 0px;
		overflow: hidden;
		border-top-left-radius: 3px;
		margin-top: 0px;
		border-bottom-right-radius: 3px;
		margin-bottom: 0px;
		padding-right: 5px;
	}
	.text20-clz {
		border: 1px solid #0ba1f7;
		padding-top: 5px;
		border-bottom-left-radius: 3px;
		color: #0ba1f7;
		padding-left: 5px;
		padding-bottom: 5px;
		border-top-right-radius: 3px;
		margin-right: 5px;
		margin-left: 0px;
		overflow: hidden;
		border-top-left-radius: 3px;
		margin-top: 0px;
		border-bottom-right-radius: 3px;
		margin-bottom: 0px;
		padding-right: 5px;
	}
	.text6-clz {
		border: 1px solid #0ba1f7;
		padding-top: 5px;
		border-bottom-left-radius: 3px;
		color: #0ba1f7;
		padding-left: 5px;
		padding-bottom: 5px;
		border-top-right-radius: 3px;
		margin-right: 5px;
		margin-left: 0px;
		overflow: hidden;
		border-top-left-radius: 3px;
		margin-top: 0px;
		border-bottom-right-radius: 3px;
		margin-bottom: 0px;
		padding-right: 5px;
	}
	.container22243 {
		padding-left: 0px;
		padding-right: 0px;
	}
</style>
