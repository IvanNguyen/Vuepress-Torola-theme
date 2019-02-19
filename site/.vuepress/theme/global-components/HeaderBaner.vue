<template>
    <section class="hero hero-fullscreen" 
				 style="background-color: rgb(0, 0, 0);">

			<!-- Slider -->
			<div id="mySlider" class="carousel slide" data-ride="carousel">
				<ol class="carousel-indicators">
					<li data-target="#mySlider" data-slide-to="0" class="active"></li>
					<li data-target="#mySlider" data-slide-to="1"></li>
					<li data-target="#mySlider" data-slide-to="2"></li>
				</ol>
				<div class="carousel-inner" role="listbox">
					<div class="carousel-item active">
						<img src="../../public/images/gallery/108.jpg" alt="First slide">
						<div class="carousel-caption d-none d-md-block">
							<h3>Martian Child</h3>
							<p>Design / Art</p>
						</div>
					</div>
					<div class="carousel-item">
						<img src="../../public/images/gallery/109.jpg" alt="Second slide">
						<div class="carousel-caption d-none d-md-block">
							<h3>Swept Away</h3>
							<p>Design / Art</p>
						</div>
					</div>
					<div class="carousel-item">
						<img src="../../public/images/gallery/107.jpg" alt="Third slide">
						<div class="carousel-caption d-none d-md-block">
							<h3>New Sol, New Hope</h3>
							<p>Design / Art</p>
						</div>
					</div>
				</div>
				<a class="carousel-control-prev" href="#mySlider" role="button" data-slide="prev">
					<span class="carousel-control-prev-icon" aria-hidden="true"></span>
					<span class="sr-only">Previous</span>
				</a>
				<a class="carousel-control-next" href="#mySlider" role="button" data-slide="next">
					<span class="carousel-control-next-icon" aria-hidden="true"></span>
					<span class="sr-only">Next</span>
				</a>
			</div>
			<!-- /Silder -->

		</section>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
/* .hero {
    height: 100%;
} */
.hero-fullscreen {
    height: calc(100vh - 65px);
}
.carousel-inner img {
    display: inline-block;
    width: 100%;
    height: calc(100vh - 65px);
}
</style>