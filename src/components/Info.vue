<template>
	<section>
				<div class="container">
					<div class="row">
						<div class="col-md-8 app-content">
							<div class="feature-content">
								<div id="resources">
				          <ul>
				            <li>
				              <a href="https://spike.readme.io/docs">
				                <div class="icon docs"></div>
				                <div class="text">
				                  <h4>Where To Find Us</h4>
				                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				                  tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
				                  quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
				                  consequat.</p>
				                </div>
				              </a>
				            </li>
				            <li>
				              <a href="https://medium.com/static-dev">
				                <div class="icon articles"></div>
				                <div class="text">
				                  <h4>Why Happy Tree Yoga?</h4>
				                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				                  tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
				                  quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
				                  consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
				                  cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
				                  proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
				                </div>
				              </a>
				            </li>
				            <li>
				              <a href="https://plugins.spike.cf">
				                <div class="icon plugins"></div>
				                <div class="text">
				                  <h4>Class Structure</h4>
				                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				                  tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
				                  quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
				                  consequat.</p>
				                </div>
				              </a>
				            </li>
				            <li>
				              <a href="https://gitter.im/static-dev/spike">
				                <div class="icon community"></div>
				                <div class="text">
				                  <h4>Class Times</h4>
				                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				                  tempor incididunt ut labore et dolore magna aliqua.</p>
				                </div>
				              </a>
				            </li>
				            <li>
				              <a href="https://spike.readme.io/docs/built-with-spike">
				                <div class="icon built-with-spike"></div>
				                <div class="text">
				                  <h4>Learn More...</h4>
				                  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				                  tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
				                  quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
				                  consequat.</p>
				                </div>
				              </a>
				            </li>
				          </ul>
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
.app-content {
	margin: auto;
}

.feature-content {
  padding: 8rem 0;
  overflow: hidden;
  margin: auto;
}

#resources {}

#resources ul {
  margin: 0;
  padding: 0;
  list-style: none
}

#resources li {
  margin-bottom: 2em
}

#resources a {
  color: #4F5354;
  text-decoration: none;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
  -webkit-transition: opacity .25s ease;
  transition: opacity .25s ease
}

#resources a:hover {
  opacity: 0.8
}

#resources .icon {
  -webkit-box-flex: 0;
      -ms-flex: 0 0 85px;
          flex: 0 0 85px;
  height: 85px;
  margin-right: 30px;
  border-radius: 999px;
  background-color: #ffc38c;
  background-position: center center;
  background-repeat: no-repeat
}

@media (max-width: 450px) {

  #resources .icon {
    display: none
  }
}

/*#resources .icon.docs {
  background-image: url('/img/docs.svg')
}

#resources .icon.articles {
  background-image: url('/img/articles.svg')
}

#resources .icon.plugins {
  background-image: url('/img/plugins.svg')
}

#resources .icon.community {
  background-image: url('/img/community.svg')
}

#resources .icon.built-with-spike {
  background-image: url('/img/built-with-spike.svg')
}*/

#resources h4 {
  font-size: 1.1em;
  margin: 0 0 .25em 0;
  font-weight: 600
}

#resources p {
  margin: 0;
  color: rgb(132, 135, 135)
}
</style>