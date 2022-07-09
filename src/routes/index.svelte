<script>
	import { GithubIcon } from 'svelte-feather-icons';
	import { projects } from '@src/utils/projectsData.svelte';
	import { skills } from '@src/utils/skillsData.svelte';
</script>

<!-- intro -->
<div class="mb-10 flex flex-wrap">
	<img src="/vp.JPG" alt="vp" class="rounded-full w-40 h-40 mr-5" />
	<p
		class="justify-end text-lg sm:text-xl rounded-r-xl rounded-bl-xl sm:rounded-bl-none sm:rounded-tl-xl h-[38px] px-1 mt-12 bg-white bg-blue-600 flex items-center "
	>
		Hello I'm Varun Pereira, Software Engineer!
	</p>
</div>

<!-- skills -->
<p id="skills" class="text-center font-bold text-2xl my-5">Skills</p>
<div class="flex flex-wrap">
	{#each skills as skill}
		<div
			class="mb-4 mr-4  text-sm rounded-lg bg-white text-black font-bold text-sm  px-2 flex items-center"
		>
			{skill}
		</div>
	{/each}
</div>

<!-- projects -->
<div class="flex justify-center my-5">
	<p id="projects" class="text-center font-bold text-2xl mr-3">Projects</p>
	<a href="https://github.com/varunpereira" target="_blank" class="mr-2"
		><GithubIcon class="w-6 h-6 hover:text-gray-400 mt-2" /></a
	>
</div>
<div class="flex flex-wrap text-white">
	{#each projects as project}
		<a
			href={project.href}
			target="_blank"
			class="max-w-[16rem] max-h-[32rem] pb-4 mr-4  text-sm rounded-lg bg-white hover:bg-gray-300 "
		>
			<img class="h-44 w-96 rounded-t-lg object-cover" src={project.src} alt="img" />
			<div class="pt-4 px-4">
				<p class="h-8  font-bold tracking-tight text-gray-900 ">{project.title}</p>
				<p class="h-24 font-normal text-gray-700">
					{project.desc}
				</p>
			</div>
		</a>
	{/each}
</div>

<!-- experience -->
<p id="experience" class="text-center font-bold text-2xl my-5">Experience</p>
<div class="flex justify-center">
	<div class="text-left">
		<p class="font-semibold">Software Engineer Apprentice - Slalom</p>
		<p>(Jan 2022 - Dec 2022, 1 year)</p>
		<p>- developed and tested web apps for clients</p>
		<br />
		<p class="font-semibold">Software Engineering Tutor - Code Camp</p>
		<p>(Jan 2021 - Dec 2021, 1 year)</p>
		<p>- taught basic frontend skills to children</p>
		<br />
		<p class="font-semibold">Web Designer - Career Success Australia</p>
		<p>(Nov 2020, 1 month)</p>
		<p>- designed a job employment website</p>
	</div>
</div>

<!-- education -->
<p id="education" class="text-center font-bold text-2xl my-5">Education</p>
<div class="flex justify-center">
	<div class="text-left">
		<p class="font-semibold">Bachelor of Software Engineering - RMIT</p>
		<p>(2020 - 2023, 4 years)</p>
		<p>- volunteered in software engineering tutoring and clubs</p>
	</div>
</div>
