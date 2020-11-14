<script>
	import Intro from '../components/index/Intro.svelte';
</script>

<style>

	.products {
		text-align: left;
		display: flex;
		justify-content: space-evenly;
		margin-top: 2em;
	}

	.padded {
		margin-left: 4em;
		margin-top: 2em;
	}

	h2 {
		transition: color 200ms ease-in-out;
	}

	h2:hover {
		color: rgb(83, 83, 83);
	}

	@media (max-width: 600px) {
		.padded {
			margin-left: 1em;
		}
	}

</style>

<svelte:head>
	<title>
		PARADIGMA.MEDIA Werbung Berlin |
		Wir bieten Ihnen Schilder & Lichtwerbung mit speziellem Know-How in Form, Farbe und 
		Funktionalität. Von der Visitenkarte über Leuchtkasten bis zur Großflächen Plakat Kampagne, 
		Qualität bestimmt über den Erfolg ihrer Werbung. 
		Durch Vereinigung neuester Technologien, Kreativität, viel Wissen sowie 
		langjähriger Erfahrung erfüllen wir alle Anforderungen an moderne Werbetechnik.
	</title>
</svelte:head>

<Intro />

<div class="products">
	<div>
		<div>
			<a href="lichtwerbung">
				<h2>Lichtwerbung</h2>
			</a>
			<div class="padded">
				<a href="foliendesign">
					<h2>Foliendesign</h2>
				</a>
				<div class="padded">
					<a href="digitaldruck">
						<h2>Digitaldruck</h2>
					</a>
				</div>
			</div>
		</div>
	</div>
	<div>
		<div>
			<a href="messe-ausstellung">
				<h2>Messe & Ausstellung</h2>
			</a>
			<div class="padded">
				<a href="planung-montage">
					<h2>Planung & Montage</h2>
				</a>
				<div class="padded">
					<a href="kontakt">
						<h2>Angebotsanfrage</h2>
					</a>
				</div>
			</div>
		</div>
	</div>
</div>