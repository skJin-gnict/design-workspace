<script>
	import anime from 'animejs/lib/anime.es';
	import { onMount } from 'svelte';
	onMount(() => {
		// JS 코드 시작
		anime({
			targets: '.el',
			translateX: 270
		});
		// JS 코드 끝
	});
</script>

<div>
	<!-- HTML 코드 시작 -->
	<div class="el">test</div>
	<!-- HTML 코드 끝 -->
</div>

<style>
	/* CSS 코드 시작 */
	div {
		background-color: black;
		display: inline;
	}
	/* CSS 코드 끝*/
</style>
