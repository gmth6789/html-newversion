<template>
	<view class="container container22243">
		<view class="flex flex-wrap diygw-col-24 flex-direction-column flex6-clz">
			<view class="flex flex-wrap diygw-col-24 flex-direction-column items-center flex-clz">
				<image src="/static/favicon.png" class="image1-size diygw-image diygw-col-0 image1-clz" mode="widthFix"></image>
				<view class="diygw-col-0 diygw-text-lg"> 邓志锋 </view>
				<view class="diygw-col-0 diygw-text-sm"> 研发部 </view>
			</view>
			<view class="flex diygw-col-24 justify-around flex-nowrap white flex2-clz">
				<view class="flex flex-wrap diygw-col-6 flex-direction-column items-center flex3-clz">
					<view class="diygw-col-0 diygw-text-lg text-blue"> 10 </view>
					<view class="diygw-col-0 text-grey"> 累计年假 </view>
				</view>
				<view class="flex flex-wrap diygw-col-6 flex-direction-column items-center flex7-clz">
					<view class="diygw-col-0 diygw-text-lg text-blue"> 2 </view>
					<view class="diygw-col-0 text-grey"> 累计调休 </view>
				</view>
				<view class="flex flex-wrap diygw-col-6 flex-direction-column items-center flex9-clz">
					<view class="diygw-col-0 diygw-text-lg text-blue"> 0 </view>
					<view class="diygw-col-0 text-grey"> 累计病假 </view>
				</view>
			</view>
			<view class="flex diygw-col-24 white list-clz">
				<view class="diygw-list small not-remark">
					<view style="" class="diygw-item col-100 row arrow solid-bottom list-item-clz">
						<view class="diygw-avatar list-icon-clz">
							<image mode="aspectFit" class="diygw-avatar-img" src="/static/db.png"></image>
							<view class="diygw-tag badge empty list-badge-0 red"></view>
						</view>
						<view class="content">
							<view class="title"> 待办流程 </view>
						</view>
					</view>
					<view style="" class="diygw-item col-100 row arrow solid-bottom list-item-clz">
						<view class="diygw-avatar list-icon-clz">
							<image mode="aspectFit" class="diygw-avatar-img" src="/static/jbqx.png"></image>
						</view>
						<view class="content">
							<view class="title"> 经办流程 </view>
						</view>
					</view>
					<view style="" class="diygw-item col-100 row arrow solid-bottom list-item-clz">
						<view class="diygw-avatar list-icon-clz">
							<image mode="aspectFit" class="diygw-avatar-img" src="/static/jbqx.png"></image>
						</view>
						<view class="content">
							<view class="title"> 我的流程 </view>
						</view>
					</view>
					<view style="" class="diygw-item col-100 row arrow solid-bottom list-item-clz">
						<view class="diygw-avatar list-icon-clz">
							<image mode="aspectFit" class="diygw-avatar-img" src="/static/yj3.png"></image>
							<view class="diygw-tag badge list-badge-3 red"> 1 </view>
						</view>
						<view class="content">
							<view class="title"> 我的邮件 </view>
						</view>
					</view>
					<view style="" class="diygw-item col-100 row arrow solid-bottom list-item-clz">
						<view class="diygw-avatar list-icon-clz">
							<image mode="aspectFit" class="diygw-avatar-img" src="/static/jbqx.png"></image>
						</view>
						<view class="content">
							<view class="title"> 经办流程 </view>
						</view>
					</view>
					<view style="" class="diygw-item col-100 row arrow solid-bottom list-item-clz">
						<view class="diygw-avatar list-icon-clz">
							<image mode="aspectFit" class="diygw-avatar-img" src="/static/jbqx.png"></image>
						</view>
						<view class="content">
							<view class="title"> 经办流程 </view>
						</view>
					</view>
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
				globalData: {}
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
	.flex6-clz {
		z-index: 100;
		background-repeat: no-repeat;
		background-size: contain;
		background-image: url(/static/OA.png);
	}
	.flex-clz {
		margin-left: 5px;
		z-index: 100;
		color: #ffffff;
		width: calc(100% - 5px - 5px) !important;
		margin-top: 20px;
		margin-bottom: 5px;
		margin-right: 5px;
	}
	.image1-clz {
		border-bottom-left-radius: 50%;
		border-top-right-radius: 50%;
		margin-right: 5px;
		background-color: #ffffff;
		margin-left: 5px;
		flex-shrink: 0;
		box-shadow: 0px 1px 3px rgba(31, 31, 31, 0.16);
		overflow: hidden;
		width: 48px !important;
		border-top-left-radius: 50%;
		margin-top: 10px;
		border-bottom-right-radius: 50%;
		margin-bottom: 10px;
	}
	.image1-size {
		height: 48px !important;
		width: 48px !important;
	}
	.flex2-clz {
		padding-top: 20px;
		border-bottom-left-radius: 10px;
		z-index: 100;
		padding-left: 10px;
		padding-bottom: 20px;
		border-top-right-radius: 10px;
		margin-right: 10px;
		background-color: rgba(217, 217, 217, 0.13);
		margin-left: 10px;
		box-shadow: 0px 2px 4px 3px rgba(181, 207, 255, 0.5);
		overflow: hidden;
		width: calc(100% - 10px - 10px) !important;
		border-top-left-radius: 10px;
		margin-top: 10px;
		border-bottom-right-radius: 10px;
		margin-bottom: 10px;
		padding-right: 10px;
	}
	.flex3-clz {
		z-index: 100;
		border-right: 1px solid #eee;
	}
	.flex7-clz {
		z-index: 100;
		border-right: 1px solid #eee;
	}
	.flex9-clz {
		z-index: 100;
		border-right: 1px solid #eee;
	}
	.list-clz {
		background-color: rgba(217, 217, 217, 0.13);
		margin-left: 10px;
		border-bottom-left-radius: 10px;
		box-shadow: 0px 2px 4px 3px rgba(181, 207, 255, 0.5);
		overflow: hidden;
		width: calc(100% - 10px - 10px) !important;
		border-top-left-radius: 10px;
		margin-top: 10px;
		border-top-right-radius: 10px;
		border-bottom-right-radius: 10px;
		margin-bottom: 10px;
		margin-right: 10px;
	}
	.list-item-clz {
		margin: 0px;
		padding: 10px;
	}
	.list-item-clz .list-icon-clz {
		width: 40px;
		height: 40px;
		font-size: calc(40px - 4px) !important;
	}

	.list-badge-0 {
		padding-left: 0px;
		padding-right: 0px;
		right: 2px;
		top: 0px;
	}
	.list-badge-3 {
		padding-left: 0px;
		padding-right: 0px;
		right: -7px;
		top: -5px;
	}
	.container22243 {
		padding-left: 0px;
		padding-right: 0px;

		background-position: top center;
		background-size: contain;
		background-repeat: no-repeat;
	}
</style>
