<script>
	// Import any fonts if needed (this depends on your setup)
	import { onMount } from 'svelte';

	// Define your array of words
	const words = [
		'Commandments',
		'Instructions',
		'Regulations',
		'Statutes',
		'History',
		'Culture',
		'Order',
		'Rules',
		'Truth',
		'Laws'
	];

	let currentWordIndex = 0; // Track the current word index
	let currentWord = words[currentWordIndex]; // Initial word

	// Cycle through words at an interval
	onMount(() => {
		const interval = setInterval(() => {
			// Update the index and word
			currentWordIndex = (currentWordIndex + 1) % words.length;
			currentWord = words[currentWordIndex];
		}, 2000); // Change every 2 seconds (adjust as needed)

		// Cleanup the interval on component destruction
		return () => clearInterval(interval);
	});
</script>

<!-- Component Markup -->
<section class="intro">
	<p class="intro-text">It’s time to learn about the...</p>
	<h1 class="highlighted-text">
		<span class="highlighted-word" style="color: var(--blue-color)">{currentWord}</span> in the Bible.
	</h1>
</section>

<section class="study-info">
	<!-- Left Section -->
	<div class="left-section">
		<p class="highlight-text">EVERY SATURDAY</p>
		<p>
			We gather at 12pm - 3pm to study our history found within the Bible. Be ready to learn,
			bringing your Bible and your notebook. We look forward to seeing you!
		</p>
	</div>

	<!-- Middle Section -->
	<div class="middle-section">
		<p>
			Unfortunately, today’s church-goers are misled and taught things that go contrary to the word
			of God. We don’t like it. Time is precious and to be taught lies is a work of evil. Here at
			the Light of Zion we combat Satan by speaking the truth of the word of God. We’re in this
			world but we’re not of it.
		</p>
		<p>
			Be different, be unique to be... Israel. The data shows that there are 2 main
			religions—Christianity and Islam, more than anything we want to promote the truth and in doing
			so we have to separate the word of God (found in the Bible) from religion.
		</p>
	</div>

	<!-- Right Section -->
	<div class="right-section">
		<blockquote>“We ought to obey God rather than Men.”</blockquote>
		<p>— Acts 5:29-31</p>
	</div>
</section>

<!-- Styling -->
<style>
	:root {
		--blue-color: #0056b3; /* Set your accent color here */
	}

	.intro {
		text-align: left;
		font-family: Helvetica, Arial, sans-serif;
		display: flex;
		justify-self: flex-start;
		flex-direction: column;
		align-items: flex-start;
		width: 100%;
	}

	.intro-text {
		font-family: 'Times New Roman', Times, serif;
		font-style: italic;
		color: #333;
		margin-bottom: 0.5rem;
	}

	.highlighted-text {
		font-size: 2rem;
		font-weight: 400;
		color: #000;
	}

	.highlighted-word {
		font-weight: bold;
		font-size: 2.5rem;
		transition: opacity 0.5s ease-in-out;
		display: inline-block;
	}

	/* Grid layout for three-column structure */
	.study-info {
		display: grid;
		grid-template-columns: 1fr 1fr 1fr;
		gap: 2rem;
		padding: 1rem;
		font-family: Helvetica, Arial, sans-serif;
		color: #333;
	}

	/* Left Section Styles */
	.left-section {
		text-align: left;
	}

	.highlight-text {
		color: var(--blue-color);
		font-weight: bold;
		font-size: 0.9rem;
		text-transform: uppercase;
		margin-bottom: 0.5rem;
	}

	/* Middle Section Styles */
	.middle-section {
		font-style: italic;
		line-height: 1.5;
	}

	/* Right Section Styles */
	.right-section {
		text-align: right;
		color: #666;
	}

	blockquote {
		color: var(--blue-color);
		font-size: 1.2rem;
		margin: 0;
		font-style: italic;
	}

	.right-section p {
		margin-top: 0.5rem;
		font-size: 0.9rem;
		color: #555;
	}
</style>
