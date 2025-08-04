<div class="min-h-screen bg-gradient-to-b from-green-800 via-green-600 to-green-400 p-4">
	<!-- Stadium atmosphere -->
	<div class="max-w-6xl mx-auto">
		
		<!-- Stadium lights -->
		<div class="flex justify-between mb-8">
			<div class="w-8 h-16 bg-yellow-300 rounded-full shadow-lg animate-pulse"></div>
			<div class="w-8 h-16 bg-yellow-300 rounded-full shadow-lg animate-pulse delay-200"></div>
			<div class="w-8 h-16 bg-yellow-300 rounded-full shadow-lg animate-pulse delay-400"></div>
			<div class="w-8 h-16 bg-yellow-300 rounded-full shadow-lg animate-pulse delay-600"></div>
		</div>

		<!-- Main Scoreboard -->
		<div class="bg-black rounded-lg border-8 border-yellow-400 shadow-2xl overflow-hidden mb-8">
			
			<!-- Scoreboard Header -->
			<div class="bg-red-600 text-white text-center py-4">
				<h1 class="text-4xl font-bold tracking-wider">⚾ BASEBALL SCOREBOARD ⚾</h1>
				<p class="text-lg mt-2">LINCOLN PARK STADIUM</p>
			</div>

			<!-- Team Names and Scores -->
			<div class="bg-black text-white p-6">
				<div class="grid grid-cols-2 gap-8 mb-6">
					
					<!-- Home Team -->
					<div class="text-center">
						<div class="bg-blue-600 rounded-lg p-4 mb-4">
							<h2 class="text-3xl font-bold">🏠 LIONS</h2>
							<p class="text-sm opacity-80">HOME</p>
						</div>
						<div class="bg-green-500 rounded-lg p-6">
							<div class="text-6xl font-bold">7</div>
							<p class="text-lg">RUNS</p>
						</div>
					</div>

					<!-- Away Team -->
					<div class="text-center">
						<div class="bg-red-600 rounded-lg p-4 mb-4">
							<h2 class="text-3xl font-bold">🚀 EAGLES</h2>
							<p class="text-sm opacity-80">AWAY</p>
						</div>
						<div class="bg-green-500 rounded-lg p-6">
							<div class="text-6xl font-bold">4</div>
							<p class="text-lg">RUNS</p>
						</div>
					</div>
				</div>

				<!-- Inning by Inning Score -->
				<div class="bg-gray-800 rounded-lg p-4 mb-6">
					<h3 class="text-xl font-bold text-center mb-4 text-yellow-400">📊 INNING BY INNING</h3>
					
					<!-- Inning Headers -->
					<div class="grid grid-cols-11 gap-2 text-center text-sm font-bold border-b border-gray-600 pb-2 mb-2">
						<div class="text-yellow-400">TEAM</div>
						<div class="bg-yellow-400 text-black rounded px-1">1</div>
						<div class="bg-yellow-400 text-black rounded px-1">2</div>
						<div class="bg-yellow-400 text-black rounded px-1">3</div>
						<div class="bg-yellow-400 text-black rounded px-1">4</div>
						<div class="bg-yellow-400 text-black rounded px-1">5</div>
						<div class="bg-yellow-400 text-black rounded px-1">6</div>
						<div class="bg-yellow-400 text-black rounded px-1">7</div>
						<div class="bg-yellow-400 text-black rounded px-1">8</div>
						<div class="bg-yellow-400 text-black rounded px-1">9</div>
						<div class="text-red-400 font-bold">R</div>
					</div>
					
					<!-- Eagles Score -->
					<div class="grid grid-cols-11 gap-2 text-center mb-2">
						<div class="text-red-400 font-bold text-sm">EAGLES</div>
						<div class="bg-gray-700 rounded px-2 py-1">0</div>
						<div class="bg-gray-700 rounded px-2 py-1">2</div>
						<div class="bg-gray-700 rounded px-2 py-1">0</div>
						<div class="bg-gray-700 rounded px-2 py-1">1</div>
						<div class="bg-gray-700 rounded px-2 py-1">0</div>
						<div class="bg-gray-700 rounded px-2 py-1">0</div>
						<div class="bg-gray-700 rounded px-2 py-1">1</div>
						<div class="bg-gray-700 rounded px-2 py-1">0</div>
						<div class="bg-gray-700 rounded px-2 py-1">0</div>
						<div class="bg-red-500 rounded px-2 py-1 font-bold">4</div>
					</div>
					
					<!-- Lions Score -->
					<div class="grid grid-cols-11 gap-2 text-center">
						<div class="text-blue-400 font-bold text-sm">LIONS</div>
						<div class="bg-gray-700 rounded px-2 py-1">1</div>
						<div class="bg-gray-700 rounded px-2 py-1">0</div>
						<div class="bg-gray-700 rounded px-2 py-1">3</div>
						<div class="bg-gray-700 rounded px-2 py-1">0</div>
						<div class="bg-gray-700 rounded px-2 py-1">2</div>
						<div class="bg-gray-700 rounded px-2 py-1">0</div>
						<div class="bg-gray-700 rounded px-2 py-1">0</div>
						<div class="bg-gray-700 rounded px-2 py-1">1</div>
						<div class="bg-gray-700 rounded px-2 py-1">0</div>
						<div class="bg-blue-500 rounded px-2 py-1 font-bold">7</div>
					</div>
				</div>

				<!-- Game Status -->
				<div class="grid grid-cols-3 gap-4 text-center">
					
					<!-- Current Inning -->
					<div class="bg-purple-600 rounded-lg p-4">
						<h4 class="text-sm font-bold mb-2">INNING</h4>
						<div class="text-3xl font-bold">9th</div>
						<div class="text-sm mt-1">⬇️ BOTTOM</div>
					</div>

					<!-- Count -->
					<div class="bg-orange-600 rounded-lg p-4">
						<h4 class="text-sm font-bold mb-2">COUNT</h4>
						<div class="flex justify-center space-x-2">
							<div class="text-center">
								<div class="text-2xl font-bold">2</div>
								<div class="text-xs">BALLS</div>
							</div>
							<div class="text-3xl">-</div>
							<div class="text-center">
								<div class="text-2xl font-bold">1</div>
								<div class="text-xs">STRIKES</div>
							</div>
						</div>
					</div>

					<!-- Outs -->
					<div class="bg-red-600 rounded-lg p-4">
						<h4 class="text-sm font-bold mb-2">OUTS</h4>
						<div class="flex justify-center space-x-1">
							<div class="w-6 h-6 bg-red-400 rounded-full border-2 border-white"></div>
							<div class="w-6 h-6 bg-gray-600 rounded-full border-2 border-white"></div>
							<div class="w-6 h-6 bg-gray-600 rounded-full border-2 border-white"></div>
						</div>
						<div class="text-2xl font-bold mt-2">1</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Baseball Diamond Display -->
		<div class="bg-brown-600 rounded-lg p-8 mb-8 relative overflow-hidden">
			<div class="bg-brown-400 absolute inset-0 rounded-lg"></div>
			<div class="relative z-10">
				<h3 class="text-center text-white text-xl font-bold mb-6">⚾ DIAMOND STATUS</h3>
				
				<!-- Baseball Diamond -->
				<div class="relative w-48 h-48 mx-auto">
					<!-- Diamond shape -->
					<div class="absolute inset-0 transform rotate-45 bg-green-300 border-4 border-white rounded-lg"></div>
					
					<!-- Bases -->
					<div class="absolute top-0 left-1/2 transform -translate-x-1/2 -translate-y-2 w-6 h-6 bg-white rounded-sm rotate-45 border-2 border-gray-400">
						<!-- 2nd Base -->
					</div>
					<div class="absolute top-1/2 right-0 transform translate-x-2 -translate-y-1/2 w-6 h-6 bg-yellow-400 rounded-sm rotate-45 border-2 border-gray-400">
						<!-- 1st Base - Runner on base -->
						<div class="absolute inset-0 flex items-center justify-center">
							<span class="text-xs transform -rotate-45">🏃</span>
						</div>
					</div>
					<div class="absolute bottom-0 left-1/2 transform -translate-x-1/2 translate-y-2 w-6 h-6 bg-white rounded-sm rotate-45 border-2 border-gray-400">
						<!-- Home Plate -->
					</div>
					<div class="absolute top-1/2 left-0 transform -translate-x-2 -translate-y-1/2 w-6 h-6 bg-yellow-400 rounded-sm rotate-45 border-2 border-gray-400">
						<!-- 3rd Base - Runner on base -->
						<div class="absolute inset-0 flex items-center justify-center">
							<span class="text-xs transform -rotate-45">🏃</span>
						</div>
					</div>
					
					<!-- Pitcher's mound -->
					<div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-4 h-4 bg-brown-500 rounded-full border-2 border-white"></div>
				</div>
				
				<p class="text-center text-white mt-4 text-sm">Runners on 1st and 3rd base!</p>
			</div>
		</div>

		<!-- Fun Statistics -->
		<div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-8">
			
			<!-- Player Stats -->
			<div class="bg-white rounded-lg p-6 shadow-lg">
				<h4 class="text-xl font-bold text-center mb-4 text-gray-800">🏆 PLAYER SPOTLIGHT</h4>
				<div class="text-center">
					<div class="text-3xl mb-2">⚾</div>
					<h5 class="font-bold text-lg">Mike Rodriguez</h5>
					<p class="text-sm text-gray-600">Lions #23</p>
					<div class="mt-4 grid grid-cols-2 gap-2 text-center text-sm">
						<div class="bg-blue-100 rounded p-2">
							<div class="font-bold">3</div>
							<div>HITS</div>
						</div>
						<div class="bg-green-100 rounded p-2">
							<div class="font-bold">2</div>
							<div>RBIs</div>
						</div>
					</div>
				</div>
			</div>

			<!-- Weather -->
			<div class="bg-white rounded-lg p-6 shadow-lg">
				<h4 class="text-xl font-bold text-center mb-4 text-gray-800">🌤️ WEATHER</h4>
				<div class="text-center">
					<div class="text-4xl mb-2">☀️</div>
					<div class="text-2xl font-bold">75°F</div>
					<p class="text-sm text-gray-600 mt-2">Sunny</p>
					<p class="text-xs text-gray-500">Wind: 5 mph E</p>
					<p class="text-xs text-gray-500">Perfect day for baseball!</p>
				</div>
			</div>

			<!-- Next Up -->
			<div class="bg-white rounded-lg p-6 shadow-lg">
				<h4 class="text-xl font-bold text-center mb-4 text-gray-800">⚾ UP NEXT</h4>
				<div class="text-center">
					<div class="text-3xl mb-2">🥎</div>
					<h5 class="font-bold text-lg">Sarah Chen</h5>
					<p class="text-sm text-gray-600">Eagles #7</p>
					<div class="mt-4 text-sm">
						<div class="bg-gray-100 rounded p-2 mb-2">
							<span class="font-bold">AVG:</span> .325
						</div>
						<div class="bg-yellow-100 rounded p-2">
							<span class="font-bold">HR:</span> 12
						</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Tailwind Learning Section -->
		<div class="bg-gray-900 text-white rounded-lg p-6">
			<h3 class="text-2xl font-bold text-center mb-6 text-yellow-400">🎓 What We're Learning with Tailwind</h3>
			
			<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
				<div>
					<h4 class="text-lg font-bold mb-3 text-green-400">🎨 Layout & Design</h4>
					<ul class="space-y-2 text-sm">
						<li>• <code class="bg-gray-700 px-2 py-1 rounded">grid grid-cols-2</code> - Grid layouts for scores</li>
						<li>• <code class="bg-gray-700 px-2 py-1 rounded">bg-gradient-to-b</code> - Stadium grass effect</li>
						<li>• <code class="bg-gray-700 px-2 py-1 rounded">rounded-lg border-8</code> - Scoreboard styling</li>
						<li>• <code class="bg-gray-700 px-2 py-1 rounded">shadow-2xl</code> - Depth and realism</li>
					</ul>
				</div>
				
				<div>
					<h4 class="text-lg font-bold mb-3 text-blue-400">⚡ Interactive Elements</h4>
					<ul class="space-y-2 text-sm">
						<li>• <code class="bg-gray-700 px-2 py-1 rounded">animate-pulse</code> - Stadium lights</li>
						<li>• <code class="bg-gray-700 px-2 py-1 rounded">transform rotate-45</code> - Diamond shape</li>
						<li>• <code class="bg-gray-700 px-2 py-1 rounded">absolute relative</code> - Positioning bases</li>
						<li>• <code class="bg-gray-700 px-2 py-1 rounded">text-6xl font-bold</code> - Big, bold scores</li>
					</ul>
				</div>
			</div>
		</div>
	</div>
</div>
