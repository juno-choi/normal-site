<script>
	import Header from '../Header.svelte';
  	import "../styles.css";
</script>
<div>
	<div class="relative bg-white">
	<div class="mx-auto max-w-7xl px-6">
			<Header />
			<slot />
		</div>
	</div>
</div>
