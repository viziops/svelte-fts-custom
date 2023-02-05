
  <header class="main-header">
    <a href="/" class="brand-logo">
      <div class="brand-logo-name">Feed the SEARCH</div>
    </a>
    <nav class="main-nav">
      <ul>
        <li><a href="discover.html">Discover</a></li>
        <li><a href="join.html">Join</a></li>
      </ul>
    </nav>
  </header>
  <section class="home-main-section">
    <div class="img-wrapper">
      <div class="lady-image"></div>
    </div>
    <div class="call-to-action">
      <h1 class="title">Performance and Prominence</h1>
      <span class="subtitle">Custom designed fullstack websites and content that deliver results</span>
      <a href="join.html" class="btn">Here's How</a>
    </div>
  </section>
  <div class="home-page-circle-1"></div>
  <div class="home-page-circle-2"></div>
  <div class="home-page-circle-3"></div>


<style>
  .home-main-section {
	display: flex;
	align-items: stretch;
	justify-content: space-between;
	flex-grow: 1;
}

.home-main-section .img-wrapper {
	flex-grow: 1;
	flex-direction: column;
	display: flex;
	align-items: stretch;
	justify-content: flex-end;
}

.home-main-section .lady-image {
	background-image: url(images/landing-page-girl.png);
	flex-grow: 1;
	max-height: 70vh;
	min-width: 30vw;
	background-size: contain;
	background-repeat: no-repeat;
	background-position: bottom left;
}

.home-main-section .call-to-action {
	display: flex;
	flex-direction: column;
	align-items: flex-start;
	margin: 1rem;
	align-self: center;
}

@media (max-width: 900px) {
	.home-main-section .img-wrapper {
		display: none;
	}

	.home-main-section {
		justify-content: center;
	}
}

.home-page-circle-1 {
	position: absolute;
	width: 15vw;
	height: 15vw;
	border-radius: 50%;
	background-color: rgb(188, 58, 128, 0.1);
	bottom: 2vw;
	left: 5vw;
	z-index: -1;
}

.home-page-circle-2 {
	position: absolute;
	width: 25vw;
	height: 25vw;
	border-radius: 50%;
	background-color: rgb(52, 87, 178, 0.1);
	top: 15vh;
	left: 30vw;
	z-index: -1;
}

.home-page-circle-3 {
	position: absolute;
	overflow: hidden;
	width: 45vw;
	height: 45vw;
	bottom: 0;
	right: 0;
	z-index: -1;
}

.home-page-circle-3::before {
	content: '';
	transform: translate(40%, 40%);
	position: absolute;
	height: 100%;
	width: 100%;
	border-radius: 50%;
	background-color: rgb(52, 87, 178, 0.1);
}


</style>
