<script>
	import { MenuIcon } from 'svelte-feather-icons';
	import { goto } from '$app/navigation';
</script>

<header class="relative mb-10 min-w-min bg-black py-4  md:flex md:items-center md:justify-between">
	<div class="md:mr-5 mb-1 px-0 flex items-center justify-between ">
		<h1 class="text-xl">
			<a href="/" class="flex font-bold no-underline hover:text-gray-400">
				<img src="/favicon.jpg" alt="logo" class="rounded-sm w-5 h-5 mt-1 mr-2"/>
				<span class="justify-end pb-1">Varun Pereira</span>
			</a>
		</h1>
		<button>
			<MenuIcon class="mb-1 h-7 w-7 hover:text-gray-400 md:hidden" />
		</button>
	</div>
	<ul class="list-reset md:flex md:items-center">
		<li class="nav-item pr-5">
			<a href="#projects" class="hover:text-gray-400">
				<span class="pr-1">Projects</span>
			</a>
		</li>
		<li class="nav-item">
			<a href="#skills" class="hover:text-gray-400">
				<span class="pr-1">Skills</span>
			</a>
		</li>
	</ul>
</header>
