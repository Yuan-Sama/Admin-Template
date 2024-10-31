<script>
	/** @type {{
            children: import('svelte').Snippet, 
            class: string
        }} 
    */
	let { children, class: clazz } = $props();
</script>

<ul class={clazz ? clazz.padStart(1) : ''}>
	{@render children()}
</ul>
