<script lang="ts">
	import './+layout.scss';
	import './xtras.css';
    import { onMount } from 'svelte';
	import Navbar from '$lib/Navbar.svelte';

	onMount(async () => {
		let font = new FontFace("inter", "url(../src/inter.woff2)")

		await font.load()

		document.fonts.add(font)
		
	})


	
</script>
<Navbar></Navbar>
<slot></slot>




