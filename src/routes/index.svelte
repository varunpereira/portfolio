<script>
	import { GithubIcon } from 'svelte-feather-icons';
</script>

<div class="mb-10 flex flex-wrap">
	<img src="/vp.JPG" alt="vp" class="rounded-full w-40 h-40 mr-5" />
	<p
		class="justify-end text-lg sm:text-xl rounded-r-xl rounded-bl-xl sm:rounded-bl-none sm:rounded-tl-xl h-[38px] px-1 mt-12 bg-white bg-blue-600 flex items-center "
	>
		Hello I'm Varun Pereira, Software Engineer!
	</p>
</div>

<p id="skills" class="text-center font-bold text-2xl my-5">Skills</p>
<div class="flex flex-wrap">
	<div
		class="mb-4 mr-4  text-sm rounded-lg bg-white text-black font-bold text-sm  px-2 flex items-center"
	>
		HTML, CSS, JS, React
	</div>
	<div
		class="mb-4 mr-4  text-sm rounded-lg bg-white text-black font-bold text-sm  px-2 flex items-center"
	>
		Next, SvelteKit
	</div>
	<div
		class="mb-4 mr-4  text-sm rounded-lg bg-white text-black font-bold text-sm  px-2 flex items-center"
	>
		HTTP, REST, Node, Express
	</div>
	<div
		class="mb-4 mr-4  text-sm rounded-lg bg-white text-black font-bold text-sm  px-2 flex items-center"
	>
		MongoDB, SQL, MySQL
	</div>
	<div
		class="mb-4 mr-4  text-sm rounded-lg bg-white text-black font-bold text-sm  px-2 flex items-center"
	>
		Git, GitHub
	</div>
	<div
		class="mb-4 mr-4  text-sm rounded-lg bg-white text-black font-bold text-sm  px-2 flex items-center"
	>
		Docker, Testing, Cypress
	</div>
	<div
		class="mb-4 mr-4  text-sm rounded-lg bg-white text-black font-bold text-sm  px-2 flex items-center"
	>
		Agile, Scrum
	</div>
	<div
		class="mb-4 mr-4  text-sm rounded-lg bg-white text-black font-bold text-sm  px-2 flex items-center"
	>
		Java, Spring
	</div>
</div>

<div class="flex justify-center my-5">
	<p id="projects" class="text-center font-bold text-2xl mr-3">Projects</p>
	<a href="https://github.com/varunpereira" target="_blank" class="mr-2"
		><GithubIcon class="w-6 h-6 hover:text-gray-400 mt-2" /></a
	>
</div>
<div class="flex flex-wrap text-white">
	<!-- 1 -->
	<a
		href="https://denify.vercel.app/"
		target="_blank"
		class="max-w-[16rem] max-h-[32rem] mb-4 mr-4  text-sm rounded-lg bg-white hover:bg-gray-300 "
	>
		<img class="h-44 w-96 rounded-t-lg object-cover" src="/denify.jpg" alt="profile" />
		<div class="px-5 pt-5">
			<p class="h-8  font-bold tracking-tight text-gray-900 ">Denify (commerce)</p>
			<p class="h-16 font-normal text-gray-700">
				Like Amazon, this product based web app lets you: login, search, cart, pay, sell, review, message, account.
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
		href="https://showify.vercel.app/"
		target="_blank"
		class="max-w-[16rem] max-h-[32rem] mb-4 mr-4  text-sm rounded-lg bg-white hover:bg-gray-300 "
	>
		<img class="h-44 w-96 rounded-t-lg object-cover" src="/showify.jpg" alt="profile" />
		<div class="px-5 pt-5">
			<p class="h-8  font-bold tracking-tight text-gray-900 ">Showify (media)</p>
			<p class="h-16 font-normal text-gray-700">
				Like IMDb, this show based web app lets you: login, search, review, account.
			</p>
		</div>
	</a>
	<!-- 3 -->
	<a
		href="https://zenify.vercel.app/"
		target="_blank"
		class="max-w-[16rem] max-h-[32rem] mb-4 mr-4  text-sm rounded-lg bg-white hover:bg-gray-300 "
	>
		<img class="h-44 w-96 rounded-t-lg object-cover" src="/zenify.jpg" alt="profile" />
		<div class="px-5 pt-5">
			<p class="h-8  font-bold tracking-tight text-gray-900 ">Zenify (web)</p>
			<p class="h-16 font-normal text-gray-700">Like SvelteKit, this web framework reimagines the developer experience. </p>
		</div>
	</a>
	<!-- 4 -->
	<a
		href="https://ramify.vercel.app/"
		target="_blank"
		class="max-w-[16rem] max-h-[32rem] mb-4 mr-4  text-sm rounded-lg bg-white hover:bg-gray-300 "
	>
		<img class="h-44 w-96 rounded-t-lg object-cover" src="/favicon.jpg" alt="profile" />
		<div class="px-5 pt-5">
			<p class="h-8  font-bold tracking-tight text-gray-900 ">Ramify (gaming)</p>
			<p class="h-16 font-normal text-gray-700">Created my own game. TBA!</p>
		</div>
	</a>
</div>

<p id="experience" class="text-center font-bold text-2xl my-5">Experience</p>
<div class="flex justify-center">
	<div class="text-left ">
		<p class="font-semibold">Software Engineer Apprentice, Slalom</p>
		<p>(Jan 2022 - Dec 2022, 1 year)</p>
		<p>-developed and tested web apps for clients</p>
		<br />
		<p class="font-semibold">Software Engineering Tutor, Code Camp</p>
		<p>(Jan 2021 - Dec 2021, 1 year)</p>
		<p>-taught basic frontend skills to children</p>
		<br />
		<p class="font-semibold">Web Designer, Career Success Australia</p>
		<p>(Nov 2020, 1 month)</p>
		<p>-designed a job employment website</p>
	</div>
</div>

<p id="education" class="text-center font-bold text-2xl my-5">Education</p>
<div class="flex justify-center">
	<div class="text-left">
		<p class="font-semibold">Bachelor of Software Engineering, RMIT</p>
		<p>(2020 - 2023, 4 years full time)</p>
		<p>-volunteered in software engineering tutoring and clubs</p>
	</div>
</div>
