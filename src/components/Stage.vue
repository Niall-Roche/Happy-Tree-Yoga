<template>
	<div id="stage">
		<div id="stage-caption">
			<div class="app-title animated fadeInLeft">
				<h1 class="display-3">Happy Tree Yoga</h1>
				<div class="container sign-up-container">
					<div class="app-sign-up">
						<span>Sign up for our newsletter</span>
						<div class="input-group">
				      <span class="input-group-btn">
				        <button class="btn btn-success" type="button">Go!</button>
				      </span>
				      <input type="email" class="form-control" placeholder="Enter your email address">
				    </div>
			    </div>
				</div>
			</div>
	  </div>
	</div>
</template>

<script>
	export default {
	
	}
</script>

<style scoped>

#stage {
	background: url('/src/assets/yoga-mat-orange.jpg') center center no-repeat;
	background-size: cover;
	color: white;
	height: 100%;
	width: 100%;
	display: flex;
	align-items: center;
}

#stage-caption {
	font-size: 1.4rem;
	font-weight: 200;
	max-width: 60rem;
	text-align: center;
}

#stage-caption h1 {
	font-weight: bold;
	color: white;
	text-transform: uppercase;
	font-family: HappyTreeYoga;
}

.display-3 {
	transition: all .2s ease-in-out;
}

.display-3:hover {
	cursor: pointer;
	transform: scale(1.3);
}

.app-title {
	width: 30%;
	margin-left: 50px;
	letter-spacing: 5px;
}

.app-sign-up {
	margin-top: 50px;
	letter-spacing: 3px;
}

.sign-up-container {
	background-color: rgba(0,0,0,0.4);
	padding-bottom: 10px;
}
</style>