<template>
	<view>
		<view class="room" > 
			<view class="type">
				<!-- 下拉列表-->
				<form action="/demo/demo_form.asp">
				<select name="分类">
				<option value="跑步" selected>跑步</option>
				</select>
				</form>
			</view>
			
			</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {			
			};
		}
	}
</script>

<style>
.room {
	    background-color:'#e5e5e5';
	    color:white;
		padding:56rpx;
	} 
  select { height: 100rpx;
  			width: auto;
  
  }
 .num {
  	font-size: 36rpx;
  	color: black;
  	position: absolute;
  	margin-left:400rpx;
	padding-top: -20rpx;
  }
  .type {
  	font-size: 36rpx;
  	color: black;
  	position:absolute;
  	margin-left:-50rpx;
	margin-top: -50rpx;
	padding-top: 20rpx
  	
  }
  
</style>
