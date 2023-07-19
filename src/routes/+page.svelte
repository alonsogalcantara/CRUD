<script>
    import Header from '../modules/Header.svelte'
    import Footer from '../modules/Footer.svelte'
</script>

<section class="layout">
	<Header/>

	<div class="main">
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae adipisci libero ea magnam eos,
		molestiae repudiandae tempore eaque neque voluptatibus dolores deserunt aspernatur? Dolor,
		labore! Voluptatibus deleniti doloremque ratione corrupti! Sequi, sunt vitae? Quaerat saepe
		doloremque non impedit ab corporis, nulla, quis accusamus aperiam fugit cum minus officia
		tenetur tempore error ut mollitia dolorum exercitationem quae facilis. Illum, nulla esse. Ad
		temporibus nobis voluptatem, aliquid velit obcaecati dicta asperiores dolore, nemo error ab, non
		quidem eveniet. Est nihil dolores iste natus rerum, iusto autem quo aperiam, hic ipsa
		perferendis non? Tempore recusandae, sapiente praesentium ipsa repudiandae impedit. Voluptas
		quaerat aspernatur tenetur molestias tempora nobis reiciendis beatae! Doloremque alias, cum
		suscipit asperiores quaerat cumque culpa dicta ipsa dolorum praesentium aspernatur? Reiciendis!
		Eos vel cum exercitationem dolorum tempore mollitia iure, quasi optio voluptas rem veniam
		similique harum sit, est doloremque inventore pariatur, recusandae minus dolor aperiam earum a
		itaque nihil! Molestiae, ex! Facilis, delectus doloribus? Nostrum in suscipit at culpa commodi
		tempore voluptate repudiandae hic, consequatur unde et, pariatur neque sunt, rerum aliquam ipsum
		ullam velit aspernatur facere harum. Ex, veniam ullam. Praesentium magnam, neque assumenda, ex
		exercitationem voluptas consectetur rerum cupiditate ad, quibusdam cumque veritatis asperiores
		aspernatur obcaecati? Corrupti, quod libero blanditiis eaque minima distinctio doloremque dolore
		autem veniam. Maxime, reprehenderit. Veritatis perspiciatis, animi accusamus adipisci corporis
		ipsa eligendi modi incidunt dignissimos placeat maxime est sint, aut reprehenderit error omnis
		facere, cumque totam tenetur ut obcaecati! Dolorem eaque odit fuga inventore? Obcaecati earum
		eos tempore maiores expedita ipsum iusto accusantium? Nobis tenetur tempora cum quia
		voluptatibus perferendis, qui modi. Praesentium accusamus, hic fuga ipsam assumenda amet? Nisi
		aperiam facilis culpa alias. Sapiente quas at, nisi nam dolore unde iure molestiae corporis
		omnis pariatur, expedita velit! Id, omnis eligendi? Obcaecati suscipit magni voluptas vero
		dicta, dolorum quisquam quo, nostrum totam natus illum. Aliquam quisquam optio exercitationem
		quo quibusdam sed distinctio consequuntur? Praesentium, alias asperiores itaque reprehenderit
		dolor quos, facilis qui eveniet doloribus et perspiciatis commodi saepe eum beatae, veritatis
		totam repellat velit. Labore repudiandae amet maxime quod autem iure, perspiciatis eaque nulla
		minima provident, quisquam architecto rerum fugit? Aspernatur at distinctio, quos atque culpa,
		officia recusandae numquam dolorem similique magnam molestiae iure! Necessitatibus sapiente
		distinctio laudantium autem quas asperiores tempora quae obcaecati iusto ipsam et consequuntur
		consectetur iure aspernatur, aliquid aliquam libero, veritatis exercitationem. Laborum ducimus
		officia in? Animi blanditiis magni quas. Fugit similique recusandae provident quae quis
		assumenda hic cumque reiciendis odit debitis tempore iste nesciunt atque voluptate beatae non
		qui, repudiandae, rem reprehenderit nam! Repudiandae nobis eaque illo ducimus impedit? Officia
		repellendus a, vero excepturi magnam eaque, vel illo quos vitae adipisci earum inventore beatae
		non nihil? Dolores modi maxime quo dolore, tempora deserunt autem distinctio labore repellendus
		quaerat itaque!
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
