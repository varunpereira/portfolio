<script>
	import { GithubIcon } from 'svelte-feather-icons';
</script>

<div class="mb-10 flex">
	<img src="/vp.JPG" alt="vp" class="rounded-full w-40 h-40 mr-10" />
	<p
		class="justify-end font-bold text-2xl rounded-r-xl rounded-tl-xl h-[38px] px-1 mt-14 bg-white text-black"
	>
		Hello I'm Varun Pereira, Software Engineer!
	</p>
</div>
<p id="skills" class="text-center font-bold text-2xl my-5">Skills</p>
<div class="flex flex-wrap">
	<a
		href="https://denify.vercel.app/"
		target="_blank"
		class="mb-4 mr-4 max-w-[16rem] max-h-[32rem] text-sm rounded-lg bg-white hover:bg-gray-300 "
	>
	</a>
	<!-- <p class="w-[154px] font-bold text-sm rounded-xl h-[22px]  px-2 bg-white text-black">
		HTML, CSS, JS, React
	</p>
	<p class="w-[115px] ml-5 font-bold text-sm rounded-xl h-[22px]  px-2 bg-white text-black">
		Next, SvelteKit
	</p>
	<p class="w-[150px] ml-5 font-bold text-sm rounded-xl h-[22px]  px-2 bg-white text-black">
		HTTP, REST, Node, Express
	</p>
	<p class="w-[150px] ml-5 font-bold text-sm rounded-xl h-[22px]  px-2 bg-white text-black">
		MongoDB, SQL, MySQL
	</p>
	<p class="w-[150px] ml-5 font-bold text-sm rounded-xl h-[22px]  px-2 bg-white text-black">
		Git, GitHub
	</p>
	<p class="w-[150px] ml-5 font-bold text-sm rounded-xl h-[22px]  px-2 bg-white text-black">
		Docker, Testing, Cypress
	</p>
	<p class="w-[150px] ml-5 font-bold text-sm rounded-xl h-[22px]  px-2 bg-white text-black">
		Agile, Scrum
	</p>
	<p class="w-[150px] mt-5 font-bold text-sm rounded-xl h-[22px]  px-2 bg-white text-black">
		Java, Spring
	</p> -->
</div>

<div class="flex justify-center my-5">
	<p id="projects" class="text-center font-bold text-2xl mr-3">Projects</p>
	<a href="https://github.com/varunpereira/public" target="_blank" class="mr-2"
		><GithubIcon class="w-6 h-6 hover:text-gray-400 mt-2" /></a
	>
</div>
<div class="flex flex-wrap text-white">
	<!-- 1 -->
	<a
		href="https://denify.vercel.app/"
		target="_blank"
		class="mb-4 mr-4 max-w-[16rem] max-h-[32rem] text-sm rounded-lg bg-white hover:bg-gray-300 "
	>
		<img class="h-44 w-96 rounded-t-lg object-cover" src="/denify.jpg" alt="profile" />
		<div class="px-5 pt-5">
			<p class="h-16  font-bold tracking-tight text-gray-900 ">Ecommerce Store - Denify</p>
			<p class="h-16 font-normal text-gray-700">
				Created my own ecommerce store that's similar to Amazon.
			</p>
			<!-- <button
				class="cursor-pointer inline-flex w-full items-center justify-center rounded-lg bg-black py-2 m font-medium text-white "
			>
				Get Code
			</button> -->
		</div>
	</a>
	<!-- 2 -->
	<a
		href="https://zenify.vercel.app/"
		target="_blank"
		class="mb-4 mr-4 max-w-[16rem] max-h-[32rem] text-sm rounded-lg bg-white hover:bg-gray-300 "
	>
		<img class="h-44 w-96 rounded-t-lg object-cover" src="/zenify.jpg" alt="profile" />
		<div class="px-5 pt-5">
			<p class="h-16  font-bold tracking-tight text-gray-900 ">Web Framework - Zenify</p>
			<p class="h-16 font-normal text-gray-700">Created my own web framework and languages.</p>
		</div>
	</a>
</div>
