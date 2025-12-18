<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="min-h-screen bg-[#f5f5f5] flex items-center justify-center px-6">
	<div class="text-center">
		<h1 class="font-serif text-6xl text-gray-900 mb-4">Error {page.status}</h1>
		<p class="text-gray-500 text-lg mb-8">{page.error?.message ?? "Something went wrong."}</p>
		<a href="/" class="bg-black text-white px-6 py-3 rounded text-sm font-medium hover:bg-gray-800 transition-colors inline-block">
			Go back home
		</a>
	</div>
</main>
