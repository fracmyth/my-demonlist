<div class="min-h-screen bg-gradient-to-b from-black via-purple-900 to-black relative overflow-hidden">
	
	<!-- Stars Background -->
	<div class="absolute inset-0">
		<div class="absolute top-10 left-10 w-1 h-1 bg-white rounded-full animate-pulse"></div>
		<div class="absolute top-20 right-20 w-1 h-1 bg-white rounded-full animate-pulse delay-100"></div>
		<div class="absolute top-32 left-1/4 w-1 h-1 bg-white rounded-full animate-pulse delay-200"></div>
		<div class="absolute top-16 right-1/3 w-1 h-1 bg-white rounded-full animate-pulse delay-300"></div>
		<div class="absolute top-40 left-3/4 w-1 h-1 bg-white rounded-full animate-pulse delay-400"></div>
		<div class="absolute top-60 left-1/5 w-1 h-1 bg-white rounded-full animate-pulse delay-500"></div>
		<div class="absolute bottom-40 right-1/4 w-1 h-1 bg-white rounded-full animate-pulse delay-600"></div>
		<div class="absolute bottom-20 left-2/3 w-1 h-1 bg-white rounded-full animate-pulse delay-700"></div>
		<div class="absolute top-80 right-10 w-1 h-1 bg-white rounded-full animate-pulse delay-800"></div>
		<div class="absolute bottom-60 left-10 w-1 h-1 bg-white rounded-full animate-pulse delay-900"></div>
	</div>

	<!-- Solar System Container -->
	<div class="absolute inset-0 flex items-center justify-center">
		<div class="relative w-96 h-96">
			
			<!-- Sun (Center) -->
			<div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-16 h-16 bg-gradient-to-br from-yellow-300 via-orange-400 to-red-500 rounded-full shadow-lg animate-pulse">
				<!-- Sun rays effect -->
				<div class="absolute inset-0 bg-yellow-300 rounded-full animate-ping opacity-20"></div>
				<div class="absolute inset-0 bg-orange-400 rounded-full animate-pulse"></div>
			</div>

			<!-- Mercury Orbit & Planet -->
			<div class="absolute inset-0 border border-gray-500 rounded-full opacity-30 animate-spin" style="animation-duration: 8s;">
				<div class="absolute top-0 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-2 h-2 bg-gray-400 rounded-full"></div>
			</div>

			<!-- Venus Orbit & Planet -->
			<div class="absolute inset-2 border border-gray-500 rounded-full opacity-30 animate-spin" style="animation-duration: 12s;">
				<div class="absolute top-0 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-3 h-3 bg-yellow-600 rounded-full"></div>
			</div>

			<!-- Earth Orbit & Planet -->
			<div class="absolute inset-6 border border-gray-500 rounded-full opacity-30 animate-spin" style="animation-duration: 16s;">
				<div class="absolute top-0 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-4 h-4 bg-gradient-to-br from-blue-400 to-green-500 rounded-full">
					<!-- Moon -->
					<div class="absolute -top-1 -right-2 w-1 h-1 bg-gray-300 rounded-full animate-spin" style="animation-duration: 2s;"></div>
				</div>
			</div>

			<!-- Mars Orbit & Planet -->
			<div class="absolute inset-10 border border-gray-500 rounded-full opacity-30 animate-spin" style="animation-duration: 24s;">
				<div class="absolute top-0 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-3 h-3 bg-red-500 rounded-full"></div>
			</div>

			<!-- Jupiter Orbit & Planet -->
			<div class="absolute inset-16 border border-gray-500 rounded-full opacity-30 animate-spin" style="animation-duration: 32s;">
				<div class="absolute top-0 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-8 h-8 bg-gradient-to-br from-orange-300 via-yellow-600 to-red-700 rounded-full">
					<!-- Jupiter's red spot -->
					<div class="absolute top-2 left-1 w-2 h-1 bg-red-800 rounded-full opacity-80"></div>
				</div>
			</div>

			<!-- Saturn Orbit & Planet -->
			<div class="absolute inset-20 border border-gray-500 rounded-full opacity-30 animate-spin" style="animation-duration: 40s;">
				<div class="absolute top-0 left-1/2 transform -translate-x-1/2 -translate-y-1/2">
					<!-- Saturn -->
					<div class="w-6 h-6 bg-gradient-to-br from-yellow-400 to-orange-500 rounded-full"></div>
					<!-- Saturn's rings -->
					<div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-10 h-10 border border-gray-400 rounded-full opacity-60"></div>
					<div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-12 h-12 border border-gray-300 rounded-full opacity-40"></div>
				</div>
			</div>
		</div>
	</div>

	<!-- Planet Information Panel -->
	<div class="absolute top-8 left-8 bg-black/60 backdrop-blur-lg text-white rounded-lg p-6 max-w-md border border-gray-600">
		<h2 class="text-2xl font-bold mb-4 text-yellow-400">🌌 Mini Solar System</h2>
		<div class="space-y-3 text-sm">
			<div class="flex items-center space-x-3">
				<div class="w-3 h-3 bg-yellow-500 rounded-full animate-pulse"></div>
				<span><strong>Sun:</strong> Our star, center of the solar system</span>
			</div>
			<div class="flex items-center space-x-3">
				<div class="w-2 h-2 bg-gray-400 rounded-full"></div>
				<span><strong>Mercury:</strong> Closest to the sun (8s orbit)</span>
			</div>
			<div class="flex items-center space-x-3">
				<div class="w-2 h-2 bg-yellow-600 rounded-full"></div>
				<span><strong>Venus:</strong> Hottest planet (12s orbit)</span>
			</div>
			<div class="flex items-center space-x-3">
				<div class="w-3 h-3 bg-gradient-to-br from-blue-400 to-green-500 rounded-full"></div>
				<span><strong>Earth:</strong> Our home with moon (16s orbit)</span>
			</div>
			<div class="flex items-center space-x-3">
				<div class="w-2 h-2 bg-red-500 rounded-full"></div>
				<span><strong>Mars:</strong> The red planet (24s orbit)</span>
			</div>
			<div class="flex items-center space-x-3">
				<div class="w-4 h-4 bg-gradient-to-br from-orange-300 to-red-700 rounded-full"></div>
				<span><strong>Jupiter:</strong> Largest planet (32s orbit)</span>
			</div>
			<div class="flex items-center space-x-3">
				<div class="w-3 h-3 bg-yellow-400 rounded-full relative">
					<div class="absolute inset-0 border border-gray-400 rounded-full transform scale-150"></div>
				</div>
				<span><strong>Saturn:</strong> Planet with rings (40s orbit)</span>
			</div>
		</div>
	</div>

	<!-- Animation Controls Info -->
	<div class="absolute top-8 right-8 bg-black/60 backdrop-blur-lg text-white rounded-lg p-6 max-w-sm border border-gray-600">
		<h3 class="text-xl font-bold mb-4 text-cyan-400">⚡ Animation Magic</h3>
		<div class="space-y-3 text-sm">
			<div>
				<code class="bg-gray-700 px-2 py-1 rounded text-cyan-300">animate-spin</code>
				<p class="mt-1">Makes planets orbit around the sun</p>
			</div>
			<div>
				<code class="bg-gray-700 px-2 py-1 rounded text-cyan-300">animation-duration</code>
				<p class="mt-1">Different speeds for each planet</p>
			</div>
			<div>
				<code class="bg-gray-700 px-2 py-1 rounded text-cyan-300">animate-pulse</code>
				<p class="mt-1">Sun glowing effect and twinkling stars</p>
			</div>
			<div>
				<code class="bg-gray-700 px-2 py-1 rounded text-cyan-300">animate-ping</code>
				<p class="mt-1">Sun's energy radiating outward</p>
			</div>
		</div>
	</div>

	<!-- Bottom Learning Panel -->
	<div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 bg-black/60 backdrop-blur-lg text-white rounded-lg p-6 max-w-4xl border border-gray-600">
		<h3 class="text-2xl font-bold text-center mb-6 text-purple-400">🎓 What We're Learning</h3>
		
		<div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-sm">
			<div>
				<h4 class="font-bold text-green-400 mb-3">🎨 Visual Design</h4>
				<ul class="space-y-2">
					<li>• <code class="bg-gray-700 px-1 rounded">bg-gradient-to-br</code> - Planet colors</li>
					<li>• <code class="bg-gray-700 px-1 rounded">rounded-full</code> - Circular shapes</li>
					<li>• <code class="bg-gray-700 px-1 rounded">shadow-lg</code> - 3D depth effect</li>
					<li>• <code class="bg-gray-700 px-1 rounded">backdrop-blur</code> - Glass panels</li>
				</ul>
			</div>
			
			<div>
				<h4 class="font-bold text-blue-400 mb-3">🌀 Animations</h4>
				<ul class="space-y-2">
					<li>• <code class="bg-gray-700 px-1 rounded">animate-spin</code> - Orbital motion</li>
					<li>• <code class="bg-gray-700 px-1 rounded">animate-pulse</code> - Glowing effects</li>
					<li>• <code class="bg-gray-700 px-1 rounded">delay-100</code> - Staggered timing</li>
					<li>• <code class="bg-gray-700 px-1 rounded">duration-8s</code> - Custom speeds</li>
				</ul>
			</div>
			
			<div>
				<h4 class="font-bold text-yellow-400 mb-3">📐 Layout</h4>
				<ul class="space-y-2">
					<li>• <code class="bg-gray-700 px-1 rounded">absolute relative</code> - Positioning</li>
					<li>• <code class="bg-gray-700 px-1 rounded">transform</code> - Centering & rotation</li>
					<li>• <code class="bg-gray-700 px-1 rounded">inset-0</code> - Full positioning</li>
					<li>• <code class="bg-gray-700 px-1 rounded">border rounded-full</code> - Orbit paths</li>
				</ul>
			</div>
		</div>
	</div>

	<!-- Comet Animation -->
	<div class="absolute top-1/4 left-0 w-2 h-2 bg-white rounded-full animate-bounce opacity-80" style="animation-duration: 3s;">
		<!-- Comet tail -->
		<div class="absolute top-0 right-0 w-8 h-1 bg-gradient-to-r from-white to-transparent opacity-60 transform -rotate-45"></div>
	</div>

	<!-- Space Facts -->
	<div class="absolute bottom-1/4 right-8 bg-black/40 backdrop-blur text-white rounded-lg p-4 max-w-xs text-xs border border-gray-700">
		<h4 class="font-bold text-cyan-300 mb-2">🚀 Space Facts</h4>
		<ul class="space-y-1 opacity-80">
			<li>• Earth takes 365 days to orbit the sun</li>
			<li>• Jupiter is bigger than all other planets combined</li>
			<li>• Saturn's rings are made of ice and rock</li>
			<li>• Mars has the largest volcano in our solar system</li>
		</ul>
	</div>
</div>
