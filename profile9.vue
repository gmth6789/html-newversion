<template>
	<view class="container container22243">
		<view class="flex diygw-col-24 flex-direction-column justify-center items-center flex-nowrap flex-clz">
			<view class="flex diygw-col-0">
				<view class="diygw-avatar lg radius diygw-shadow bg-none">
					<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/favicon.png"></image>
				</view>
			</view>
		</view>
		<view class="diygw-col-24 logintitle-clz diygw-text-lg text-purple"> 可视化登录 </view>
		<u-form-item class="diygw-col-24 username-clz diygw-form-item-small" labelPosition="top" prop="username">
			<text class="diy-icon-my margin-right-xs" style="color: #304ffe; font-size: 16px"></text>
			<u-input :focus="usernameFocus" class="" placeholder="请输入用户名" v-model="username" type="text"></u-input>
		</u-form-item>
		<u-form-item class="diygw-col-24 password-clz diygw-form-item-small" labelPosition="top" prop="password">
			<text class="diy-icon-my margin-right-xs" style="color: #304ffe; font-size: 16px"></text>
			<u-input :focus="passwordFocus" class="" placeholder="请输入密码" v-model="password" type="text"></u-input>
		</u-form-item>
		<view class="flex diygw-col-24 button-clz">
			<button class="diygw-btn gradual-purple md radius flex-sub margin-xs button-button-clz">点击登录</button>
		</view>
		<view class="flex flex-wrap diygw-col-24 justify-between flex1-clz">
			<view class="diygw-col-0 text-clz text-purple"> 注册账号 </view>
			<view class="diygw-col-0 text1-clz text-purple"> 忘记密码 </view>
		</view>
		<view class="flex flex-wrap diygw-col-24 justify-center items-center flex2-clz">
			<view class="flex diygw-col-0 line-clz">
				<view class="diygw-pzx" style="border-bottom: 1px solid #eee"></view>
			</view>
			<view class="diygw-col-0 text2-clz text-grey"> 第三方授权登录 </view>
			<view class="flex diygw-col-0 line1-clz">
				<view class="diygw-pzx" style="border-bottom: 1px solid #eee"></view>
			</view>
		</view>
		<view class="flex diygw-col-24 justify-center">
			<view class="diygw-avatar md margin-md radius bg-none">
				<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/icon2_weixin.png"></image>
			</view>
			<view class="diygw-avatar md margin-md radius bg-none">
				<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/icon2_wb.png"></image>
			</view>
			<view class="diygw-avatar md margin-md radius bg-none">
				<image mode="aspectFit" class="diygw-avatar-img radius" src="/static/icon2_QQ.png"></image>
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
				usernameFocus: false,
				username: '',
				passwordFocus: false,
				password: ''
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
		z-index: 1000;
		background-repeat: no-repeat;
		background-size: contain;
		background-image: url(/static/grouppng);
		background-position: center center;
		height: 180px;
	}
	.logintitle-clz {
		text-align: center;
	}
	.username-clz {
		margin-left: 15px;
		border-bottom-left-radius: 50px;
		box-shadow: 0px 1px 3px 3px rgba(199, 181, 255, 0.2);
		overflow: hidden;
		width: calc(100% - 15px - 15px) !important;
		border-top-left-radius: 50px;
		margin-top: 25px;
		border-top-right-radius: 50px;
		border-bottom-right-radius: 50px;
		margin-bottom: 15px;
		margin-right: 15px;
	}
	.password-clz {
		margin-left: 15px;
		border-bottom-left-radius: 50px;
		box-shadow: 0px 1px 3px 3px rgba(199, 181, 255, 0.2);
		overflow: hidden;
		width: calc(100% - 15px - 15px) !important;
		border-top-left-radius: 50px;
		margin-top: 15px;
		border-top-right-radius: 50px;
		border-bottom-right-radius: 50px;
		margin-bottom: 15px;
		margin-right: 15px;
	}
	.button-clz {
		margin-left: 10px;
		width: calc(100% - 10px - 10px) !important;
		margin-top: 10px;
		margin-bottom: 10px;
		margin-right: 10px;
	}
	.button-button-clz {
		margin: 3px !important;
	}
	.flex1-clz {
		margin-left: 15px;
		z-index: 1000;
		width: calc(100% - 15px - 15px) !important;
		margin-top: 15px;
		margin-bottom: 15px;
		margin-right: 15px;
	}
	.text-clz {
		margin-left: 15px;
		margin-top: 0px;
		margin-bottom: 0px;
		text-align: center;
		margin-right: 15px;
	}
	.text1-clz {
		margin-left: 15px;
		margin-top: 0px;
		margin-bottom: 0px;
		text-align: center;
		margin-right: 15px;
	}
	.flex2-clz {
		margin-left: 15px;
		z-index: 1000;
		width: calc(100% - 15px - 15px) !important;
		margin-top: 25px;
		margin-bottom: 15px;
		margin-right: 15px;
	}
	.line-clz {
		flex: 1;
	}
	.text2-clz {
		margin-left: 8px;
		margin-top: 5px;
		margin-bottom: 5px;
		margin-right: 8px;
	}
	.line1-clz {
		flex: 1;
	}
	.container22243 {
		padding-left: 0px;
		padding-right: 0px;

		background-size: contain;
	}
</style>
