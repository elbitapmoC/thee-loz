<script>
	import logo from '$lib/images/loz.svg';
	import yt from '$lib/images/yt.svg';
	import fb from '$lib/images/fb.svg';
	import ig from '$lib/images/ig.svg';
	let loz = 'Thee Light Of Zion';
</script>

<footer class="bg-black text-white py-16 px-6">
	<nav
		aria-labelledby="footer-links-heading"
		class="border-t border-gray-700 pt-12 flex justify-between mt-24 mb-12"
	>
		<section aria-labelledby="newsletter-heading" class="text-center mb-12">
			<h2 id="newsletter-heading" class="text-lg font-medium mb-4 tracking-widest uppercase">
				Stay Up to Date with LOZ
			</h2>
			<form
				aria-label="Newsletter Sign-Up"
				class="flex justify-center items-center max-w-md mx-auto"
			>
				<label for="newsletter-email" class="sr-only">Enter Your Email</label>
				<input
					id="newsletter-email"
					type="email"
					placeholder="Enter Your Email"
					class="p-3 w-2/3 border-b border-gray-600 bg-black text-gray-400 placeholder-gray-500 focus:outline-none"
					required
				/>
				<button
					type="submit"
					class="p-3 bg-black text-white font-semibold uppercase transition-all"
				>
					Submit
				</button>
			</form>
		</section>
		<section>
			<h3 class="text-sm font-semibold text-gray-500 mb-4 uppercase">{loz}</h3>
			<ul class="space-y-2">
				<li>
					<a href="#" class="text-gray-300 hover:text-white transition-colors">Our Elders</a>
				</li>
				<li><a href="#" class="text-gray-300 hover:text-white transition-colors">About Us</a></li>
				<li>
					<a href="#" class="text-gray-300 hover:text-white transition-colors">Join In</a>
				</li>
				<li><a href="#" class="text-gray-300 hover:text-white transition-colors">Give</a></li>
			</ul>
		</section>

		<section>
			<h3 class="text-sm font-semibold text-gray-500 mb-4 uppercase">Locations</h3>
			<ul class="space-y-2">
				<li><a href="#" class="text-gray-300 hover:text-white transition-colors">Haiti</a></li>
				<li><a href="#" class="text-gray-300 hover:text-white transition-colors">GA</a></li>
				<li><a href="#" class="text-gray-300 hover:text-white transition-colors">FL</a></li>
			</ul>
		</section>

		<section>
			<h3 class="text-sm font-semibold text-gray-500 mb-4 uppercase">The Movement</h3>
			<ul class="space-y-2">
				<li>
					<a href="#" class="text-gray-300 hover:text-white transition-colors">Resources</a>
				</li>
				<li>
					<a href="#" class="text-gray-300 hover:text-white transition-colors">Calender</a>
				</li>
				<li>
					<a href="#" class="text-gray-300 hover:text-white transition-colors">Events</a>
				</li>
				<li>
					<a href="#" class="text-gray-300 hover:text-white transition-colors">News</a>
				</li>
			</ul>
		</section>
	</nav>

	<!-- Social Media Icons -->
	<section
		class="flex flex-col sm:flex-row justify-between border-t border-gray-700 pt-6 text-right text-gray-400"
	>
		<p class="text-sm mb-4 sm:mb-0">© 2024 Thee Light of Zion</p>
		<aside class="flex space-x-6">
			<a
				href="https://www.youtube.com/@TheeLightofZion"
				aria-label="YouTube"
				class="hover:text-red-600 transition-colors"
			>
				<img src={yt} alt="YouTube" class="w-6 h-6" />
			</a>
			<a
				href="https://www.instagram.com/theelightofzion/"
				aria-label="Instagram"
				class="hover:text-pink-500 transition-colors"
			>
				<img src={ig} alt="Instagram" class="w-6 h-6" />
			</a>
			<a
				href="https://www.facebook.com/TheeL.O.Z.Network/"
				aria-label="Facebook"
				class="hover:text-blue-600 transition-colors"
			>
				<img src={fb} alt="Facebook" class="text-white w-6 h-6" />
			</a>
		</aside>
	</section>
</footer>
