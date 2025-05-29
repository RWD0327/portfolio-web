<script>
	import '../app.css';
</script>

<div class="min-h-screen flex flex-col">
	<header class="header flex flex-col md:flex-row justify-between items-center p-4 gap-4 md:gap-0">
		<div class="logo">
			<a href="/" class="text-2xl font-bold">My Svelte App</a>
		</div>
		<nav class="navbar w-full md:w-auto">
			<ul class="flex flex-col md:flex-row md:space-x-4 space-y-2 md:space-y-0 items-center">
				<li><a href="/">Home</a></li>
				<li><a href="/about">About</a></li>
				<li><a href="/contact">Contact</a></li>
			</ul>
		</nav>
	</header>

	<main class="main-content p-4 flex-1">
		<slot />
	</main>

	<footer class="text-center p-4">
		<p>&copy; 2023 My Svelte App</p>
	</footer>
</div>
