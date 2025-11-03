<script lang="ts">
	import ProjectCard from "$lib/components/ProjectCard.svelte";
</script>

<title>Luca Stenson | Game Programmer</title>

<div class="space-y-6 text-black dark:text-white">
	<div class="space-y-4">
		<p class="text-xl">
			Hi, I'm a graduate game programmer focused on gameplay, graphics, and engine programming. I Enjoy investigating problems and developing efficient solutions that improve designers&apos; workflows. I have experience in Unreal, Unity, and Godot, and I'm currently building a custom engine in C++ with Vulkan.
		</p>
		<p class="text-xl">
			Take a look at my favourite projects below.
		</p>
	</div>
	
	<h1 class="text-3xl font-bold">
		My Gameplay Programming Projects
	</h1>
	
	<div class="flex flex-wrap justify-center gap-6">
		<ProjectCard title="Dance Brawler" description="A rhythm game disguised as a fighting game." backgroundImage="/dance-brawler/thumbnail.jpg" logos={["/logos/unity.svg", "/logos/csharp.svg"]} link="/dance-brawler"></ProjectCard>
		<ProjectCard title="Crimson Dust" description="Volunteer game project with a multidisciplinary team of designers and artists." backgroundImage="/crimson-dust/thumbnail.jpg" logos={["/logos/unreal.svg", "/logos/cpp.svg"]} link="/crimson-dust"></ProjectCard>
		<ProjectCard title="Game Feel Demo" description="Super Mario 3D World-inspired platformer." backgroundImage="/game-feel-demo/thumbnail.jpg" logos={["/logos/godot.svg"]} link="/game-feel-demo"></ProjectCard>
		<ProjectCard title="LIDAR" description="The player fires rays which create dots when hitting the invisible environment." backgroundImage="/lidar/thumbnail.png" logos={["/logos/godot.svg"]} link="/lidar"></ProjectCard>
		<ProjectCard title="Doctor Who" description="Doctor Who demos featuring a &apos;Weeping Angel&apos; and a bigger-on-the-inside TARDIS" backgroundImage="/doctor-who/thumbnail.jpg" logos={["/logos/godot.svg", "logos/csharp.svg"]} link="/doctor-who"></ProjectCard>
	</div>
	
	<h1 class="text-3xl font-bold">
		My Engine and Graphics Programming Projects
	</h1>
	
	<div class="flex flex-wrap justify-center gap-6">
		<ProjectCard title="Nightbird Engine" description="A custom game engine with Vulkan rendering." backgroundImage="/nightbird/thumbnail.jpg" logos={["/logos/cpp.svg", "/logos/vulkan.svg"]} link="/nightbird"></ProjectCard>
		<ProjectCard title="Witch Treehouse" description="A shader diorama written in C++ with OpenGL." backgroundImage="/witch-treehouse/thumbnail.jpg" logos={["/logos/cpp.svg", "/logos/opengl.svg"]} link="/witch-treehouse"></ProjectCard>
	</div>
	
	<h1 class="text-3xl font-bold">
		My Other Projects
	</h1>
	
	<div class="flex flex-wrap justify-center gap-6">
		<ProjectCard title="Web Development" description="Having some past experience with NextJS, I decided to build my portfolio and the Nightbird website using SvelteKit." backgroundImage="/web-development/thumbnail.jpg" blur={true} logos={["/logos/sveltekit.svg"]} link="/web-development"></ProjectCard>
	</div>
</div>