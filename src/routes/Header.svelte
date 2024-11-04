<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/loz.svg';
</script>

<header>
	<address class="contact-info">
		<p>2937 W. Broward Blvd.</p>
		<p>Fort Lauderdale</p>
		<p>FL, 33312</p>
	</address>

	<nav class="main-nav">
		<ul class="nav-list">
			<li><a href="/">Home</a></li>
			<li><a href="/start">Learn</a></li>
			<li><a href="/about">About</a></li>
			<li><a href="/contact">Contact Us</a></li>
			<li><a href="/holy-days">Holy Days</a></li>
			<li><a href="/false-holy-days">Holidays</a></li>
		</ul>
	</nav>
</header>

<style>
	/* Layout */
	header {
		display: flex;
		justify-content: space-between;
		align-items: flex-start;
		padding: 3rem;
	}

	/* Contact Info Styling */
	.contact-info {
		font-size: 0.9rem;
		line-height: 1.2;
		color: var(--color-text);
	}

	.nav-list {
		flex-direction: column;
		display: flex;
		gap: 0.5rem;
		list-style: none;
		margin: 0;
		padding: 0;
	}

	.nav-list li a {
		color: var(--color-text);
		font-weight: 700;
		font-size: 0.8rem;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		text-decoration: none;
		padding: 0.5rem;
		transition: color 0.2s linear;
	}

	.nav-list li a:hover {
		color: var(--color-theme-1);
	}
</style>
