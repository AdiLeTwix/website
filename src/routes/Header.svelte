<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/svelte-logo.svg';
	import github from '$lib/images/github.svg';
</script>

<header class="bg-gray-800 text-gray-100">
	<nav class="flex items-center justify-center p-5">
		<div class="flex items-center space-x-4">
		<ul class="flex justify-center space-x-10">
			<li aria-current={$page.url.pathname === '/' ? 'page' : undefined}>
				<a href="/">Home</a>
			</li>
			<li aria-current={$page.url.pathname === '/about' ? 'page' : undefined}>
				<a href="/about">About Me</a>
			</li>
			<li aria-current={$page.url.pathname.startsWith('/') ? 'page' : undefined}>
				<a href="/projects"> My projects</a>
			</li>
			<li>
				<a href="https://github.com/AdiLeTwix">GitHub</a>
			</li>
		</ul>
	</div>
	</nav>

</header>
