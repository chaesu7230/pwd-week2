<script>
	import '../app.css';
</script>

<svelte:head>
	<title>AJOU Mini Portfolio</title>
</svelte:head>

<nav>
	<a href="/">Home</a>
	<a href="/about">About</a>
	<a href="/projects">Projects</a>
</nav>

<main>
	<slot />
</main>