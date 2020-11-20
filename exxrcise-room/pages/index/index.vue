<template>
	<view>
		<xuanxiang></xuanxiang><!-- 下拉选项列表-->
		<!-- 房间个数-->
		<view class="text">
			<uni-grid :column="2">
			    <uni-grid-item class="box">
			         <view >
						 <text>一起来运动吧！！！</text>
						 <navigator url="/pages/next/next" > 
						 <button class="shape" >进入</button>
						 </navigator>
					 </view>
			    </uni-grid-item>
			    <uni-grid-item>
			      <view >
						<text >一起来运动吧！！！</text>
			      		<navigator url="/pages/next/next" > 
			      		<button class="shape" >进入</button>
			      		</navigator>
			      </view>
			    </uni-grid-item>
			    <uni-grid-item>
				<view >
						<text >挑战自我！！！</text>
			      		<navigator url="/pages/next/next" > 
			      		<button class="shape" >进入</button>
			      		</navigator>
			      </view>
			    </uni-grid-item>
			    <uni-grid-item>
			    <view >
			    		<text >挑战自我！！！</text>
			      		<navigator url="/pages/next/next" > 
			      		<button class="shape" >进入</button>
			      		</navigator>
			      </view>
			    </uni-grid-item>
			   <uni-grid-item>
			   <view >
			   		<text >挑战自我！！！</text>
			     		<navigator url="/pages/next/next" > 
			     		<button class="shape" >进入</button>
			     		</navigator>
			     </view>
			   </uni-grid-item>
			   <uni-grid-item>
			   <view >
			   		<text >挑战自我！！！</text>
			     		<navigator url="/pages/next/next" > 
			     		<button class="shape" >进入</button>
			     		</navigator>
			     </view>
			   </uni-grid-item>
			</uni-grid>
		</view>
		
	</view>
	
</template>

<script>
	import uniGrid from "@/components/uni-grid/uni-grid.vue"
	import uniGridItem from "@/components/uni-grid-item/uni-grid-item.vue"
	import xuanxiang from "@/components/xuanxiang/xuanxiang.vue"
	export default {
		data(){
				
			return{}
		},
	    components: {
			uniGrid,
			uniGridItem,
			xuanxiang 
		},	
		methods:{

		},
	}
	
</script>

<style>
  
.text {
		font-size: 36rpx;
		color:#00557f;
	}
.shape{	
			padding-top:2rpx;
			margin-top:110rpx;
			margin-left:240rpx;
			font-size: 20rpx;	
		}
</style>
