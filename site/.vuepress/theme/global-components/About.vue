<template>
    <section id="about" class="py-lg-13 py-8">
			<div class="container d-flex justify-content-center text-lg-center">
				<div class="col-lg-8">
					<p class="small uppercase bold mb-4 animated" style="animation: fade-in-bottom 1000ms ease 300ms 1 normal both running; opacity: 1;">Hello
						There.</p>
					<h2 class="bold animated" style="animation: fade-in-bottom 1300ms ease 500ms 1 normal both running; opacity: 1;">We're
						just two lost Souls swimming in a Fish Bowl &amp; Winning Design Awards</h2>
					<p class="small serif mt-5 animated" style="animation: fade-in-bottom 1500ms ease 400ms 1 normal both running; opacity: 1;">Lorem
						ipsum dolor sit amet, consectetur adipisicing elit. Velit, et, praesentium?<br> Odit perferendis error natus
						cum, laudantium ea!</p>
				</div>
			</div>
		</section>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
    #about {
    padding-top: 17rem !important;
    padding-bottom: 17rem !important;
    /* &.small {
        font-size: 1.19rem;
        color: #909090;
    } */
    /* &.bold {
        font-weight: 700!important;
    } */
    &.uppercase {
        text-transform: uppercase;
    }
    &.serif {
        font-family: 'Times New Roman', Times, serif;
    }
    h2 {
        font-size: 5.1rem;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    }
}
.small {
    font-size: 1.19rem!important;
    color: #909090;
}
.bold {
    font-weight: 700!important;
}
</style>
