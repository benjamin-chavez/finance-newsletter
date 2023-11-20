<!-- src/routes/Header.svelte -->

<div>
	<header class="absolute inset-x-0 top-0 z-50">
		<nav class="flex items-center justify-between p-6 lg:px-8" aria-label="Global">
			<!-- lg:flex-1 -->
			<div class="flex flex-1 justify-between">
				<a href="/" class=" -m-1.5 p-1.5 text-xl uppercase text-white sm:text-3xl">
					<span class="sr-only">Name</span>
					Newsletter
				</a>
				<a
					href="/"
					type="submit"
					class="lg:text-md -m-1.5 flex items-center p-1.5 text-sm font-semibold text-white"
					>Subscribe</a
				>
			</div>
		</nav>
	</header>
</div>
