<template>
		<nav class="navbar navbar-light bg-faded navbar-toggleable-md">
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExampleCenteredNav" aria-controls="navbarsExampleCenteredNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse justify-content-md-center animated fadeInDown" id="navbarsExampleCenteredNav">
        <ul class="navbar-nav">
          <li class="nav-item active">
		        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
		      </li>
		      <li class="nav-item">
		        <a class="nav-link" href="#">Classes</a>
		      </li>
		      <li class="nav-item">
		        <a class="nav-link" href="#">Pricing</a>
		      </li>
		      <li class="nav-item">
		        <a class="nav-link" href="#">Contact</a>
		      </li>
        </ul>
      </div>
    </nav>
</template>

<script>
	export default {

	}
</script>

<style scoped>

.navbar {
    text-align: center;
}

.nav-link {
	font-family: HappyTreeYoga;
	font-size: 24px;
	transition: all .2s ease-in-out;
	margin-left: 50px;
	margin-right: 50px;
}

.nav-item > a:hover,
.nav-item > a:focus {
  background-color: transparent;
  /*border-bottom-color: #a9a9a9;
  border-bottom-color: rgba(255,255,255,.25);*/
  transform: scale(1.4);
}
</style>