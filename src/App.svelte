<script>
 import Sidebar from './Sidebar.svelte';
	export let name;
</script>

<main>
	<Sidebar />
	<div>
		<h1>Daily Swole</h1>
	</div>
</main>

<style>
 main {
	 display: grid;
	 grid-template-columns: 5em 1fr;
 }

 div {
	 display: flex;
	 flex-direction: column;
	 align-items: center;
 }

 h1 {
	 text-transform: uppercase;
 }
</style>
