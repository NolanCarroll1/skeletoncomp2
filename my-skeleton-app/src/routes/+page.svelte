<script>
	import MyCard from './Card.svelte';
</script>

<svelte:head>
	<link rel="stylesheet" href="https://unpkg.com/tailwindcss@2.2.19/dist/tailwind.min.css" />
</svelte:head>

<MyCard type="day" />
<MyCard type="night" />
