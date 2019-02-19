<template>
    <section id="portfolio">
			<div class="container px-0">
		
				<!-- Portfolio Item -->
				<figure class=" parallax-folio-item">

					<div class="parallax-window" data-background="image/folio/1.jpg" data-parallax="scroll" data-position="center" data-bleed="10" data-image-src="../../public/images/folio/1.jpg" data-natural-width="1400" data-natural-height="900"></div>
					<figcaption >
						<div class="item-caption-inner">
							<p class="text-links">
								<a href="#">Design /</a>
								<a href="#"> Art</a>
							</p>
							<h3 class="bold uppercase">Infinite black skies</h3>
							<a href="#" class="btn style-3 border-2">View Project</a>
							
						</div>
					</figcaption>

				</figure>
				<!-- /Portfolio Item -->
			
				<!-- Portfolio Item -->
				<figure class=" parallax-folio-item">

					<div class="parallax-window tall right" data-background="image/folio/5.jpg" data-parallax="scroll" data-position="center" data-bleed="10" data-image-src="../../public/images/folio/5.jpg" data-natural-width="1400" data-natural-height="900"></div>
					<figcaption class="left-caption">
						<div class="item-caption-inner">
							<p class="text-links">
								<a href="#">Design /</a>
								<a href="#"> Art</a>
							</p>
							<h3 class="bold uppercase">We will stand tall</h3>
							<a href="#" class="btn style-3 border-2">View Project</a>
						</div>
					</figcaption>

				</figure>
				<!-- /Portfolio Item -->

				<!-- Portfolio Item -->
				<figure class=" parallax-folio-item">

					<div class="parallax-window left tall" data-background="image/folio/2.jpg" data-parallax="scroll" data-position="center" data-bleed="10" data-image-src="../../public/images/folio/2.jpg" data-natural-width="1400" data-natural-height="900"></div>
					<figcaption class="right-caption">
						<div class="item-caption-inner">
							<p class="text-links">
								<a href="#">Design /</a>
								<a href="#"> Art</a>
							</p>
							<h3 class="bold uppercase">Feel the earth move</h3>
							<a href="#" class="btn style-3 border-2">View Project</a>
						</div>
					</figcaption>

				</figure>
				<!-- /Portfolio Item -->

				<!-- Portfolio Item -->
				<figure class=" parallax-folio-item">

					<div class="parallax-window" data-background="image/folio/3.jpg" data-parallax="scroll" data-position="center" data-bleed="10" data-image-src="../../public/images/folio/3.jpg" data-natural-width="1400" data-natural-height="900" style="left:30%;"></div>

					<figcaption class="" style="left:0;">
						<div class="item-caption-inner">
							<p class="text-links">
								<a href="#">Design /</a>
								<a href="#"> Art</a>
							</p>
							<h3 class="bold uppercase">Where worlds collide</h3>
							<a href="#" class="btn style-3 border-2">View Project</a>
						</div>
					</figcaption>

				</figure>
				<!-- /Portfolio Item -->

			</div>
		</section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
#portfolio {
    .parallax-folio-item:not(:last-child) {
        margin-bottom: 170px;
    }
    .parallax-folio-item {
        position: relative;
        overflow: hidden;
        width: 100%;
        /* z-index: -1; */
        .parallax-window {
            position: relative;
            background: transparent;
            width: 70%;
            height: 450px;
            /* z-index: 0; */
        }
        .tall {
            position: relative;
            width: 50%;
            height: 740px;
        }
        .right {
            left: 40%;
        }
        .left {
            left: 10%;
        }
        figcaption {
            width: 40%;
            position: absolute;
            top: 15%;
            left: 60%;
            box-shadow: 0 10px 50px rgba(0,0,0,.1);
            .text-links {
                font-size: 20px;
                font-style: italic;
                a {
                    color: #757575;
                    position: relative;
                    text-decoration: none;
                }      
            }
            h3 {
                font-size: 4rem;
            }
        }
        .left-caption {
            left: 10%;
        }
        .right-caption {
            left: 50%;
        }
        .item-caption-inner {
            position: relative;
            padding: 30px 40px 20px;
            transition: all 1s ease;
            transition-delay: .3s;
            background-color: white;
            
        }
    }
}
[data-background],[data-poster] {
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
.btn.border-2 {
    border-width: 4px;
    line-height: 37px;
}
.btn.style-3 {
    text-transform: uppercase;
    padding: 0 10% 0 10%;
    background-color: transparent;
    border-color: #dedede;
    color: black;
    font-size: 13px!important;
    font-weight: 600
}
</style>
