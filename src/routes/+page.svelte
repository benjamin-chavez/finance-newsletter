<script>
	import Icon from './icon.svelte';
</script>

<div class="">
	<div class="relative isolate pt-14">
		<div
			class="mx-auto max-w-7xl px-6 py-24 sm:py-32 lg:flex lg:items-center lg:gap-x-10 lg:px-8 lg:py-40"
		>
			<div class="mx-auto max-w-2xl lg:mx-0 lg:flex-auto">
				<!-- <div class="flex"> -->
				<!-- <div
						class="relative flex items-center gap-x-4 rounded-full px-4 py-1 text-sm leading-6 text-gray-300 ring-1 ring-white/10 hover:ring-white/20"
					>
						<span class="font-semibold text-yellow-500">Start Reading</span>
						<span class="h-4 w-px bg-white/10" aria-hidden="true"></span>
						<a href="#" class="flex items-center gap-x-1">
							<span class="absolute inset-0" aria-hidden="true"></span>
							See past newsletters
							<svg
								class="-mr-2 h-5 w-5 text-gray-400"
								viewBox="0 0 20 20"
								fill="currentColor"
								aria-hidden="true"
							>
								<path
									fill-rule="evenodd"
									d="M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z"
									clip-rule="evenodd"
								/>
							</svg>
						</a>
					</div> -->
				<!-- </div> -->
				<h1 class="mt-10 max-w-lg text-4xl font-bold tracking-tight text-white sm:text-6xl">
					Lorem ipsum dolor sit consectetur
				</h1>
				<p class="mt-6 text-lg leading-8 text-gray-300">
					Esse id magna consectetur fugiat non dolor in ad laboris magna laborum ea consequat. Nisi
					irure aliquip nisi adipisicing veniam voluptate id. In veniam incididunt ex veniam
					adipisicing sit.
				</p>
				<!-- <div class="mt-10 flex items-center gap-x-6">
					<a
						href="#"
						class="rounded-md bg-yellow-600 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-yellow-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-yellow-600"
						>Get started</a
					>
					<a href="#" class="text-sm font-semibold leading-6 text-white"
						>Learn more <span aria-hidden="true">→</span></a
					>
				</div> -->
				<div class="mt-10 flex w-full items-center gap-x-6">
					<form class="w-full lg:w-3/4">
						<!-- mt-10 w-full max-w-xl text-center text-lg leading-8 text-gray-300 sm:w-3/4 -->
						<div class="flex flex-col gap-4 sm:flex-row">
							<label for="email-address" class="sr-only">Email address</label>
							<input
								id="email-address"
								name="email"
								type="email"
								autocomplete="email"
								required
								class="min-w-0 flex-auto rounded-md border-0 bg-white/5 px-3.5 py-2 text-white shadow-sm ring-1 ring-inset ring-white/10 focus:ring-2 focus:ring-inset focus:ring-yellow-500/50 sm:text-sm sm:leading-6"
								placeholder="Enter your email"
							/>
							<button
								type="submit"
								class="flex-none rounded-md bg-yellow-500 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-yellow-400 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-yellow-500"
								>Subscribe</button
							>
						</div>
					</form>
				</div>
			</div>
			<div
				class="ml-5 mt-16 flex items-center justify-center sm:mt-24 lg:mt-0 lg:flex-shrink-0 lg:flex-grow"
			>
				<Icon />
			</div>
		</div>
	</div>
</div>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.900);
		/* font-family: Helvetica, Arial, sans-serif; */
	}
</style>
