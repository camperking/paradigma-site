<script>
	// export let segment;
</script>

<style>
	nav {
		border-bottom: 1px solid rgba(255,62,0,0.1);
		font-weight: 300;
		box-sizing: border-box;
		max-width: 60vw;
		margin: 0 auto;
		padding: 0 1em;
		display: flex;
		justify-content: space-between;
		align-items: baseline;
		background-color: white;
	}

	.title {
		font-family: 'Rajdhani', sans-serif;
		font-size: 2rem;
		font-weight: 600;
	}
	.title span {
		color: var(--primary);
	}

	a {
		text-decoration: none;
	}

	.nav {
		display: flex;
		font-family: Roboto, sans-serif;
		font-size: 0.9rem;
		text-transform: uppercase;
		font-weight: 300;
	}

	.nav-item {
		padding: 0.6em 1em;
		cursor: pointer;
		transition: transform 200ms ease-in-out;
	}

	.nav-item:hover {
		transform: scale(1.2);
	}

	@media (max-width: 1650px) {
		nav {
			max-width: 80vw;
		}
	}

	@media (max-width: 850px) {
		nav {
			max-width: 100vw;
		}
	}

	@media (max-width: 650px) {
		.nav {
			flex-direction: column;
		}
	}
</style>

<nav>
	<div class="title">
		<a href="/">paradigma.<span>media</span></a>
	</div>
	<div class="nav">
		<div class="nav-item">
			lichtwerbung
		</div>
		<div class="nav-item">
			foliendesign
		</div>
		<div class="nav-item">
			digitaldruck
		</div>
		<div class="nav-item">
			messe & ausstellung
		</div>
		<div class="nav-item">
			planung & montage
		</div>
	</div>
</nav>
