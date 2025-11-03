<script lang="ts">
	export let title: string;
	export let description: string;
	export let backgroundImage: string | null = null;
	export let blur: boolean = false;
	export let link: string;
</script>

<a
	class="group relative overflow-hidden flex flex-col justify-end p-6 w-80 min-h-80 border-2 border-black dark:border-stone-400 text-black dark:text-white rounded-lg"
	href={link}
>
	<div
		class="absolute inset-0 bg-cover bg-center duration-200 group-hover:scale-107 filter {blur ? 'blur-sm' : ''}"
		style="background-image: {backgroundImage ? `url(${backgroundImage})` : 'none'}"
	></div>

	<div class="absolute inset-0 bg-black/10 dark:bg-black/30 transition-opacity duration-50 group-hover:opacity-0"></div>
	
	<div class="relative pointer-events-none hover-a z-10 space-y-1 p-2 bg-white/65 dark:bg-black/65 rounded-md">
		<h2 class="text-3xl font-semibold">{title}</h2>
		
		<p class="text-md">
			{description}
		</p>
	</div>
</a>