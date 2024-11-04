<script>
	import shofarloud from '$lib/images/shofarLoud.mp4';
</script>

<section class="container">
	<aside class="pb-72">
		<h1>THEE <span class="highlight">LIGHT</span> <span class="font-hel">OF</span> ZION</h1>
		<h2 class="header font-edit">Waking up the <span class="font-edit-italic">Lost Sheep</span></h2>
	</aside>

	<video controls src={shofarloud} class="video pb-72" aria-hidden="true"></video>
</section>

<style>
	/* Centering and Layout */
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	aside {
		text-align: center;
	}

	/* Typography */
	h1 {
		width: 100%;
		font-family: 'Helvetica Bold';
		margin-bottom: 0;
	}

	.highlight {
		font-weight: bold;
		color: blue;
	}

	/* Video Styling */
	.video {
		width: 100%;
		height: auto; /* Adjusts height automatically based on width */
		object-fit: cover;
		aspect-ratio: 16 / 9; /* Set a fixed aspect ratio, adjust as needed */
	}
</style>
