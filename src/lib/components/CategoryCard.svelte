<script lang="ts">
	export let title: string;
	export let link: string;
</script>

<a
	class="flex lg:flex-1 w-full h-20 justify-center items-center text-center border-2 rounded-xl hover:shadow-lg hover:scale-103 duration-100"
	href={link}
>
	<h2 class="text-3xl font-bold">
		{title}
	</h2>
</a>