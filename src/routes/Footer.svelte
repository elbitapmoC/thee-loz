<script>
	import logo from '$lib/images/loz.svg';
	import yt from '$lib/images/yt.svg';
	import fb from '$lib/images/fb.svg';
	import ig from '$lib/images/ig.svg';
	let loz = 'Thee Light Of Zion';
</script>

<footer class="bg-gray-900 text-white py-16 px-6">
	<!-- Logo Section -->
	<div class="flex justify-center mb-8">
		<img src={logo} alt="Thee Light of Zion Logo" class="w-8 h-8" />
	</div>

	<!-- Title -->
	<div class="text-center text-2xl font-semibold tracking-wide mb-10">{loz}</div>

	<!-- Newsletter Signup -->
	<div class="text-center mb-10">
		<p class="text-lg font-medium mb-4 tracking-wide uppercase">Stay Up to Date with Passion</p>
		<form class="flex justify-center items-center max-w-md mx-auto">
			<input
				type="email"
				placeholder="Enter Your Email"
				class="p-3 w-2/3 border border-gray-700 bg-gray-800 text-gray-200 rounded-l-lg placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-white focus:border-white"
				required
			/>
			<button
				type="submit"
				class="p-3 bg-white text-gray-900 font-bold rounded-r-lg hover:bg-gray-300 transition-all"
			>
				Submit
			</button>
		</form>
	</div>

	<!-- Navigation Links -->
	<div class="grid grid-cols-1 sm:grid-cols-3 gap-12 text-center mb-12">
		<div>
			<h4 class="text-base font-semibold text-gray-400 mb-4 uppercase">{loz}</h4>
			<ul class="space-y-2">
				<li><a href="#" class="text-gray-300 hover:text-white transition-colors">About Us</a></li>
				<li>
					<a href="#" class="text-gray-300 hover:text-white transition-colors">Become a Soldier</a>
				</li>
				<li><a href="#" class="text-gray-300 hover:text-white transition-colors">Our Elders</a></li>
				<li><a href="#" class="text-gray-300 hover:text-white transition-colors">Give Alms</a></li>
			</ul>
		</div>
		<div>
			<h4 class="text-base font-semibold text-gray-400 mb-4 uppercase">Locations</h4>
			<ul class="space-y-2">
				<li><a href="#" class="text-gray-300 hover:text-white transition-colors">GA</a></li>
				<li><a href="#" class="text-gray-300 hover:text-white transition-colors">FL</a></li>
				<li><a href="#" class="text-gray-300 hover:text-white transition-colors">Haiti</a></li>
			</ul>
		</div>
		<div>
			<h4 class="text-base font-semibold text-gray-400 mb-4 uppercase">The Movement</h4>
			<ul class="space-y-2">
				<li>
					<a href="#" class="text-gray-300 hover:text-white transition-colors"
						>Shofar Loud Music Group</a
					>
				</li>
				<li>
					<a href="#" class="text-gray-300 hover:text-white transition-colors">LOZ High Holy Days</a
					>
				</li>
				<li>
					<a href="#" class="text-gray-300 hover:text-white transition-colors">LOZ Resources</a>
				</li>
			</ul>
		</div>
	</div>

	<!-- Footer Bottom -->
	<article class="flex justify-between border-t border-gray-700 pt-6 text-center text-gray-400">
		<p class="text-sm mb-6">© 2024 Thee Light of Zion</p>
		<aside>
			<a href="https://www.youtube.com/@TheeLightofZion" aria-label="YouTube">
				<img src={yt} alt="YouTube" class="icon-size" />
			</a>
			<a href="https://www.instagram.com/theelightofzion/" aria-label="Instagram">
				<img src={ig} alt="Instagram" class="icon-size" />
			</a>
			<a href="https://www.facebook.com/TheeL.O.Z.Network/" aria-label="Facebook">
				<img src={fb} alt="Facebook" class="icon-size" />
			</a>
		</aside>
	</article>
</footer>

<style>
	.icon-size {
		max-width: 1.5rem;
		max-height: 1.5rem;
		width: 100%;
		height: 100%;
	}
</style>
