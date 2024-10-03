<script>
	export let name = "Default";
	export let type = "ok"; //ok, cancel
</script>

{#if type=="ok"}
	<button class="rounded-full  bg-purple-600 hover:bg-blue-500 font-bold text-gray-200 px-5 py-3 pr-8 pl-8">
		{name}
	</button>
{/if}

{#if type=="cancel"}
	<button class="text-purple-600 hover:text-blue-500 font-bold rounded-full bg-white px-5 py-3 pr-8 pl-8">
		{name}
	</button>
{/if}