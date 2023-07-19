<script>
    import Header from '../modules/Header.svelte'
    import Footer from '../modules/Footer.svelte'
</script>

<section class="layout">
	<Header/>

	<div class="main">
		<img src="https://picsum.photos/1080/720" alt="Lorem Picsum">
	</div>

    <Footer />
</section>

<style>
	.layout {
		width: auto;
		height: 768px;

		display: grid;
		grid:
			'header' auto
			'main' 1fr
			'footer' auto
			/ 1fr;
		gap: 8px;
	}

	.main {
		grid-area: main;
    }
</style>
