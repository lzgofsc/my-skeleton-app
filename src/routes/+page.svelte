<script lang="ts">
	import { Avatar, AppShell } from '@skeletonlabs/skeleton';
</script>

<AppShell slotSidebarLeft="bg-surface-500/5 w-56 p-4">
	<svelte:fragment slot="sidebarLeft">
		<!-- Insert the list: -->
		<nav class="list-nav">
			<ul>
				<li><a href="/">Home</a></li>
				<li><a href="/about">About</a></li>
			</ul>
		</nav>
		<!-- --- -->

		<div class="container mx-auto p-8 space-y-8">
			<h1 class="h1">Hello Skeleton</h1>
			<p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
			<section>
				<a class="btn variant-filled-primary" href="https://kit.svelte.dev/">SvelteKit</a>
				<a class="btn variant-filled-secondary" href="https://tailwindcss.com/">Tailwind</a>
				<a class="btn variant-filled-tertiary" href="https://github.com/">GitHub</a>
			</section>
		</div>
	</svelte:fragment>
</AppShell>
