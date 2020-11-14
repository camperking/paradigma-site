<script>
import Angebotsanfrage from "../Angebotsanfrage.svelte";


</script>

<style>
	img {
		width: 65%;
	}

	.image {
		width: 100%;
		display: grid;
		place-items: center;
	}
	
	p {
		font-family: Roboto, sans-serif;
		font-size: 1.5rem;
		font-weight: 300;
		line-height: 1.8;
		letter-spacing: 0.08em;
		margin-bottom: 0;
	}

	h1 {
		max-width: 20ch;
		margin-bottom: 1em;
	}

	.card {
		text-align: left;
		display: flex;
		justify-content: space-between;
		align-items: center;
	}

	.one, .two {
		margin: 2em 0;
	}

	@media (max-width: 600px) {
		.card {
			flex-direction: column;
		}
	}
</style>

<div class="card">
	<div class="one">
		<h1>Leidenschaft ist das beste Werkzeug</h1>
		<p>Leidenschaft-Sektor-Werbetechnik: Idee, Planung, Gestaltung, Konzept, Produktion und Montage. Sie finden bei uns das ganze Leistungspaket.</p>
	</div>
	<div class="image">
		<img src="img/paradigma.png" alt="paradigma.media Werbung Berlin" >
	</div>
</div>




<div class="card">
	<div class="image">
		<img src="img/grenzenlos.jpg" alt="Grenzenlose Möglichkeiten">
	</div>
	<div class="two">
		<h1>Qualität ist eine Lebenseinstellung</h1>
		<p>Wir entwickeln für Sie Werbeanlagen, Schilder und Wegeleitsysteme, Außenwerbung, Drucksachen, Sonderanfertigungen und vieles mehr.</p>
	</div>
</div>

<Angebotsanfrage />
<!-- <div class="anfrage">
	<Angebotsanfrage />
</div> -->