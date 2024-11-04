<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/loz.svg';
</script>

<header>
	<nav>
		<article>
			<p>2937 W. Broward Blvd.</p>
			<p>Fort Lauderdale</p>
			<p>FL, 33312</p>
		</article>
		<ul>
			<a href="/start">Learn</a>
			<!-- 
			How to Repent?
			12 Tribes
			Who are the Israelites today?
			613 LSC
			2 Kingdoms of Israel
			Christ's True Name
			Curses & Blessings (DEU 28) -->

			<a href="/about">About</a>
			<!-- 
			About	
			Beliefs
			History
			Leadership -->

			<a href="/holy-days">Holy Days</a>
			<!--
			Calendar
			Sabbath
			New Moon
			Passover / Feast of Unleavened Bread
			Day of Simon
			Feast of First Fruits
			Memorial Blowing of the Trumpets
			Day of Atonement
			Feast of Tabernacles
			Feast of Dedication
			Destruction of Nicanor
			Purim -->

			<a href="/false-holy-days">False Holidays</a>
			<!-- 
			False Christian Holidays
			Birthdays
			Christmas
			Easter
			Halloween
			Mother’s Day
			New Year’s Day
			St Patrick’s Day
			Sunday
			Thanksgiving Day
			Valentine’s Day -->

			<a href="/contact">Contact Us</a>
		</ul>
	</nav>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
	}

	nav a:hover {
		color: var(--color-theme-1);
	}

	nav {
		display: flex;
		width: 100%;
		justify-content: space-between;
		& ul {
			display: flex;
			justify-content: space-between;
			align-items: flex-end;
			gap: 1rem;
			flex-direction: column;
			list-style: none;
		}
		& a {
			display: flex;
			height: 100%;
			align-items: center;
			padding: 0 0.5rem;
			color: var(--color-text);
			font-weight: 700;
			font-size: 0.8rem;
			text-transform: uppercase;
			letter-spacing: 0.1em;
			text-decoration: none;
			transition: color 0.2s linear;
		}
	}
</style>
