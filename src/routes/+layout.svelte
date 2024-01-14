<script>
	import 'normalize.css';
</script>

<header class="header">
	<a href="/" class="home">JK Reviews</a>
	<nav>
		<a href="/books">Books</a>
		<a href="/movies">Movies</a>
		<a href="/anime">Anime</a>
	</nav>
</header>

<slot class="main" />

<footer>
	<a href="https://juliankrzysiak.com">© 2024 Julian Krzysiak</a>
	<a href="https://github.com/CastillejaCode/reviews">github </a>
</footer>

<style>
	:global(body) {
		display: flex;
		flex-direction: column;
		justify-content: space-between;
		height: 100vh;
	}

	.main {
		flex: 1;
	}

	header {
		display: flex;
		flex-direction: column;
		align-items: center;
		gap: 1rem;
		padding: 1rem;
	}

	footer {
		display: flex;
		justify-content: space-between;
		padding: 1rem;
	}
</style>
