<template>
	<div class="loading"><img src="../assets/loading.gif"  alt=""><span>{{loadingWord}}</span></div>
</template>

<script>
export default {
    name: 'loading',
    props:{
    	loadingWord:{
    		type:String
    	}
    } ,
    data () {
        return {

    	};
  	}
};
</script>

<style lang="scss" scoped>
 	@import '../base/css/base.scss';
	.loading{
		text-align: center;
		z-index: 100;
		width: 100%;				
		img{
			margin: 0 auto;
			width: 0.65rem;
			height: 0.65rem;
			vertical-align: middle;
		}
		span{
			vertical-align: middle;
			@include fz(14px)
		}
	}
</style>