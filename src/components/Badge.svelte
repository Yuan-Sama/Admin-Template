<script>
	/** @type {{
            children: import('svelte').Snippet, 
            class: string
        }} 
    */
	let { children, class: clazz } = $props();
</script>

<span
	class=" inline-block whitespace-nowrap rounded-[0.375rem] text-center align-baseline text-xs leading-[1] text-white {clazz
		? clazz.padStart(1)
		: ''}"
>
	{@render children()}
</span>
