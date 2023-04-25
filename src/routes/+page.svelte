<script>
	import { Toggle } from 'radix-svelte';

	let pressed = false;
</script>


<h1>Welcome to this Radix-svelte Sveltekit typescript template</h1>
<p>Visit <a href="https://github.com/TGlide/radix-svelte">radix-svelte</a> to read the documentation</p>

<div class="border-gray-400 border-dotted border my-4"></div>

<Toggle.Root bind:pressed class="bg-blue-400 rounded-md">
	{pressed ? 'Pressed' : 'Not pressed'}
</Toggle.Root>