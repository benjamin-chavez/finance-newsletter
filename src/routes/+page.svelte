<div>
	<div class="relative isolate px-6 pt-14 lg:px-8">
		<div class="mx-auto max-w-2xl py-32 sm:py-48">
			<div class="text-center flex flex-col items-center">
				<h1 class="text-4xl font-bold tracking-tight text-white sm:text-7xl">
					Lorem ipsum dolor sit consectetur
				</h1>
				<p class="mx-auto mt-2 max-w-xl text-center text-lg leading-8 text-gray-300">
					Reprehenderit ad esse et non officia in nulla. Id proident tempor incididunt nostrud nulla
					et culpa.
				</p>

				<form class="mx-auto mt-10 max-w-xl text-center text-lg leading-8 text-gray-300 w-3/4">
					<div class="flex gap-x-4">
						<label for="email-address" class="sr-only">Email address</label>
						<input
							id="email-address"
							name="email"
							type="email"
							autocomplete="email"
							required
							class="min-w-0 flex-auto rounded-md border-0 bg-white/5 px-3.5 py-2 text-white shadow-sm ring-1 ring-inset ring-white/10 focus:ring-2 focus:ring-inset focus:ring-indigo-500 sm:text-sm sm:leading-6"
							placeholder="Enter your email"
						/>
						<button
							type="submit"
							class="flex-none rounded-md bg-indigo-500 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-indigo-400 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-500"
							>Subscribe</button
						>
					</div>
				</form>
			</div>
		</div>
	</div>
</div>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.900);
		font-family: Helvetica, Arial, sans-serif;
	}
</style>
