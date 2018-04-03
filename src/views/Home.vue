<template>
  <div class="home">

    <div class="banner">
    	
    </div>
    <div class="main_bg">
    	<div class="main">
    		<div class="l">
    			<div class="top">
    				<img  v-for="i in arr" :src="i" alt="">
    			</div>
    			<div class="lou">
    				<p>全新楼盘</p>
    				<span>- New Apartment -</span>
    				<dl>
    					<img src="http://ccdn.goodq.top/caches/7f72634bb4b7fbd4cacee150ae5ac686/aHR0cDovLzVhNWM1YzVmNjU5NmQudDczLnFpZmVpeWUuY29tL3FmeS1jb250ZW50L3VwbG9hZHMvMjAxOC8wMS8yMmEyZTgzODY3ZDk2MzU3ZDA2YWU1N2VmYjE1NzNiZC0yODB4MTgwLmpwZw_p_p100_p_3D_p_p100_p_3D.jpg" alt="">
    					<dt>W3322-10008楼盘</dt>
    					<div class="dd">
    						<span>地区：W3322-10008</span> 
    						<span>户型:32m2-64m2</span>
    						<span>价格:21000/元m2</span>
    					</div>
    				</dl>
    			</div>
    		</div>
    		<div class="r">r</div>
    	</div>
    </div>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'
export default {
  name: 'home',
  components: {
    HelloWorld
  },
  data(){
  	return{
  		'arr':["http://ccdn.goodq.top/caches/7f72634bb4b7fbd4cacee150ae5ac686/aHR0cDovLzVhNWM1YzVmNjU5NmQudDczLnFpZmVpeWUuY29tL3FmeS1jb250ZW50L3VwbG9hZHMvMjAxOC8wMS8zNTMyOGMwMzgzNDcxMjYzYjFjMzYzNThjYjVjOTc3OC02MDB4MjA0LmpwZw_p_p100_p_3D_p_p100_p_3D.jpg","http://ccdn.goodq.top/caches/7f72634bb4b7fbd4cacee150ae5ac686/aHR0cDovLzVhNWM1YzVmNjU5NmQudDczLnFpZmVpeWUuY29tL3FmeS1jb250ZW50L3VwbG9hZHMvMjAxOC8wMS8xZWM4Yzg2ODQ5MjVkMDVhODc4MDg4M2JhYzQxOThmOC02MDB4MjA0LmpwZw_p_p100_p_3D_p_p100_p_3D.jpg","http://ccdn.goodq.top/caches/7f72634bb4b7fbd4cacee150ae5ac686/aHR0cDovLzVhNWM1YzVmNjU5NmQudDczLnFpZmVpeWUuY29tL3FmeS1jb250ZW50L3VwbG9hZHMvMjAxOC8wMS8yMmEyZTgzODY3ZDk2MzU3ZDA2YWU1N2VmYjE1NzNiZC00NzR4MTYxLmpwZw_p_p100_p_3D_p_p100_p_3D.jpg","http://ccdn.goodq.top/caches/7f72634bb4b7fbd4cacee150ae5ac686/aHR0cDovLzVhNWM1YzVmNjU5NmQudDczLnFpZmVpeWUuY29tL3FmeS1jb250ZW50L3VwbG9hZHMvMjAxOC8wMS8xODUxNThhNTMyNzA3OTcwMDM0ZjUwZDFkZjAyMGQxZi02MDB4MjA0LmpwZw_p_p100_p_3D_p_p100_p_3D.jpg"]
  	}
  }
}
</script>
<style>
	.banner{
		width: 100%;
		height: 660px;
		background-color: yellow;
	}
	.main_bg{
		width: 100%;
		height: auto;
		padding-top: 40px;
		padding-left: 80px;
		padding-right: 80px;
		box-sizing: border-box;
	}
	.main{
		padding:0 40px;
		box-sizing: border-box;
		display: flex;
		justify-content: space-between;

	}
	.main .l{
		width: 73%;
		height: auto;
	}
	.main .r{
		width: 25%;
		height: auto;
	}
	.l>.top{
		width: 100%;
		height: auto;
		display: flex;
		justify-content: space-between;
		flex-wrap: wrap;
		margin-bottom:30px;
	}
	.l>.top>img{
		width: 49%;
		margin-right: 1%;
		margin-bottom: 10px;
	}
	.lou{
		width: 99%;
		height: auto;
		margin-right: 1%;
		border: 1px solid rgba(226,226,226,1);
		color: #000000;
		overflow: hideen;
		background: #f7f7f7;
	}
	.lou>p{
		width: 100%;
		height: 25px;
		padding-top: 20px;
		box-sizing: border-box;
		text-align: center;
		font-size: 22px;
		color: #000;
		font-weight: border;
	}
	.lou>span{
		display: block;
		width: 100%;
		height: 15px;
		font-size: 14px;
		color: #666;
		margin-bottom: 20px;
	}
	.lou>dl{
		width: 33.33%;
		height: auto;
		overflow: hidden;
	}
	.lou>dl>img{
		width: 100%;
		height: 174px;
	}
	.lou>dl>dt{
		text-align: left;
		padding-left: 20px;
		box-sizing: border-box;
		width: 100%;
		font-weight: bolder;
		font-size: 16px;
		color: #000;
		margin-bottom: 20px;
		line-height: 30px;
	}
	.lou>dl>div{
		width: 100%;
		text-align: left;
		padding-left: 20px;
	}
	.lou>dl>div>span{
		display: block;
		box-sizing: border-box;
		font-size: 14px;
		color: #000;
		line-height: 24px;
	}
</style>