<template>
	<section>
			<div class="row">
			  <div class="card-group">
				  <div class="card text-center">
				    <img class="card-img" src="/src/assets/yoga-group-class.jpg" alt="Card image">
				    <div class="app-card-detail">
				    	<span class="app-card-text">Group Classes</span>
				    </div>
				    <div class="overlay">
				    	 <div class="card-text">
					    	<p>Group Classes</p>
					    	<a class="btn btn-success card-btn">Book Now <i class="fa fa-arrow-circle-right" aria-hidden="true"></i></a>
					    </div>
					  </div>
				  </div>
				  <div class="card">
				    <img class="card-img" src="/src/assets/yoga-kids.jpg" alt="Card image">
				    <div class="app-card-detail">
				    	<span class="app-card-text">Kid's Classes</span>
				    </div>
				    <div class="overlay">
					    <div class="card-text">
					    	<p>Children's Classes</p>
					    	<a class="btn btn-success card-btn">Book Now <i class="fa fa-arrow-circle-right" aria-hidden="true"></i></a>
					    </div>
					  </div>
				  </div>
				  <div class="card">
				    <img class="card-img" src="/src/assets/yoga-one-on-one.jpg" alt="Card image">
				    <div class="app-card-detail">
				    	<span class="app-card-text">Private Classes</span>
				    </div>
				    <div class="overlay">
					    <div class="card-text">
					    	<p>Private Instruction</p>
					    	<a class="btn btn-success card-btn">Book Now <i class="fa fa-arrow-circle-right" aria-hidden="true"></i></a>
					    </div>
					  </div>
				  </div>
				</div>
			</div>
	</section>
</template>

<script>
	
</script>

<style scoped>
.app-card-detail{
	position: absolute;
	z-index: 1;
	left: 25%;
	font-family: HappyTreeYoga;
	font-size: 64px;
}

.card-img {
	height: 100%;
	width: 100%;
	border-radius: 0;
	opacity: 0.5;
}

.overlay {
  position: absolute;
  z-index: 2;
  bottom: 100%;
  left: 0;
  right: 0;
  background-color: #ffc38c;
  overflow: hidden;
  width: 100%;
  height:0;
  transition: .5s ease;
}

.card:hover .overlay {
  bottom: 0;
  height: 100%;
  cursor: pointer;
}

.card-text {
  white-space: nowrap;
  color: white;
  font-size: 20px;
  position: absolute;
  overflow: hidden;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
}
</style>