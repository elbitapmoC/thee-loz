<script>
	import shofarloud from '$lib/images/shofarLoud.mp4'
</script>

<section>
	<aside class="pad-72">
		<h1>THEE <span class="highlight"> LIGHT </span> <span class="font-hel">OF</span> ZION</h1>
		<h2 class="header font-edit">Waking up the <span class="font-edit-italic">Lost Sheep</span></h2>
	</aside>
	<!-- svelte-ignore a11y-media-has-caption -->
	<video controls src={shofarloud}>
		<source src={shofarloud} type="video/mp4">
	</video>
</section>

<style>
	aside {
		text-align: center;
	}

	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	h1 {
		width: 100%;
		font-family: 'Helvetica Bold';
		margin-bottom: 0px;
		
	}
</style>
