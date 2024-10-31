<script>
	/** @type {{
	 * class?: string,
	 * collapseAtStart?: boolean,
	 * children: import('svelte').Snippet
	 * }}
	 */
	let { class: clazz = '', collapseAtStart = false, children } = $props();

	let collapse = $state(collapseAtStart);

	export function showing() {
		return !collapse;
	}

	export function show() {
		collapse = false;
	}

	export function hide() {
		collapse = true;
	}
</script>

<ul class="{clazz ? clazz.padStart(1, ' ') : ''}{collapse ? ' hidden' : ''}">
	{@render children?.()}
</ul>
