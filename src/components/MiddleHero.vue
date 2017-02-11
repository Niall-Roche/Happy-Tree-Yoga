<template>
	<section>
				<div class="middle-hero" :style="{ 'background-image': 'url(' + img + ')' }">
	        <div class="middle-hero-content">
	        </div>
	      </div>
			</section>
</template>

<script>
	export default {
			props: {
				img: String
			},
			created(){
				console.log(this.img);
			}
	}
</script>

<style>
	/* Middle hero styles
------------------------- */
.middle-hero {
    background: no-repeat center;
    background-attachment: fixed;
    background-size: cover;
    width: 100%;
    height: 400px;
}

.middle-hero-content {
    background-color: rgba(0,0,0,0.1);
    width: 100%;
    height: 100%;
}

.middle-hero .headline {
    color: #f7f7f7;
    font-size: 50px;
    font-weight: 500;
    text-align: center;
}
</style>