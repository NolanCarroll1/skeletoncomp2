<script>
	import MyButton from "./Button.svelte"
	import MyInput from "./Input.svelte"
	export let type = "day"
</script>

{#if  type=="day"}
<div class="bg-white rounded p-8 shadow flex flex-col space-y-4 m-0.5">
	  <h1 class="text-black font-bold text-center text-xl">What's your team name</h1>
		<p class="text-center text-s text-gray-400 ">The team name will be shown for all members</p>
		<MyInput/>
		<MyButton name="Confirm" type="ok"/>
		<MyButton name="Cancel" type="cancel"/>
</div>
{/if}
{#if  type=="night"}
<div class="bg-neutral-800 rounded p-8 shadow m-0.5 flex flex-col space-y-4">
	  <h1 class="text-white font-bold text-center text-xl">What's your team name</h1>
		<p class="text-center text-s text-slate-400 ">The team name will be shown for all members</p>
		<MyInput/>
		<MyButton name="Confirm" type="ok"/>
		<MyButton name="Cancel" type="cancel"/>
</div>
{/if}