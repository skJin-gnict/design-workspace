<script>
	import anime from 'animejs/lib/anime.es';
	import { onMount } from 'svelte';
	onMount(() => {
		// JS 코드 시작

		const time = 1000;
		const timeline1 = anime.timeline({
			duration: time,
			easing: 'easeOutExpo'
		});
		timeline1.add({
			targets: '.sample',
			d: [{ value: "M81 84C81 84 69.8071 65 56 65C42.1929 65 31 84 31 84C31 70.1929 42.1929 59 56 59C69.8071 59 81 70.1929 81 84Z" }]
		});

		
		// JS 코드 끝
	});
</script>

<!-- HTML 코드 시작 -->
<div class="el" />

<div>
	<svg>
		<path
			class="sample"
			d="M88.5 113C88.5 125.703 86.7025 136 74 136C61.2975 136 59 125.703 59 113C59 100.297 61.2975 90 74 90C86.7025 90 88.5 100.297 88.5 113Z"
			fill="black"
		/>


	</svg>
</div>

<!-- HTML 코드 끝 -->

<style>
	/* CSS 코드 시작 */

	/* CSS 코드 끝*/
</style>
