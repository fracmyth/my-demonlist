<svelte:head>
	<title>Animated Loading Screen</title>
</svelte:head>

<div class="relative h-screen w-full bg-gradient-to-br from-indigo-500 via-purple-500 to-pink-500 overflow-hidden">
	
	<!-- Corner decorations -->
	<div class="absolute top-5 left-5 w-20 h-20 border-2 border-white/30 border-r-0 border-b-0 rounded-tl-2xl"></div>
	<div class="absolute top-5 right-5 w-20 h-20 border-2 border-white/30 border-l-0 border-b-0 rounded-tr-2xl"></div>
	<div class="absolute bottom-5 left-5 w-20 h-20 border-2 border-white/30 border-r-0 border-t-0 rounded-bl-2xl"></div>
	<div class="absolute bottom-5 right-5 w-20 h-20 border-2 border-white/30 border-l-0 border-t-0 rounded-br-2xl"></div>

	<!-- Floating background circles -->
	<div class="absolute top-20 left-10 w-16 h-16 bg-white/10 rounded-full animate-pulse"></div>
	<div class="absolute top-60 right-20 w-10 h-10 bg-white/20 rounded-full animate-ping"></div>
	<div class="absolute bottom-32 left-1/4 w-20 h-20 bg-white/10 rounded-full animate-pulse delay-500"></div>
	<div class="absolute top-40 right-1/3 w-8 h-8 bg-white/20 rounded-full animate-ping delay-1000"></div>
	<div class="absolute bottom-20 right-10 w-12 h-12 bg-white/10 rounded-full animate-pulse delay-700"></div>

	<!-- Main loading content centered -->
	<div class="absolute inset-0 flex items-center justify-center">
		<div class="text-center text-white">
			<h1 class="text-5xl font-bold mb-8 drop-shadow-lg animate-pulse">Welcome Back!</h1>
			<p class="text-xl mb-10 opacity-80">Loading your awesome experience...</p>
			
			<!-- Spinning loader -->
			<div class="w-20 h-20 mx-auto mb-8 border-4 border-white/30 border-t-white rounded-full animate-spin"></div>
			
			<!-- Progress bar -->
			<div class="w-80 h-2 bg-white/20 rounded-full mx-auto mb-6 overflow-hidden">
				<div class="h-full bg-gradient-to-r from-blue-400 via-green-400 to-purple-400 rounded-full animate-pulse transition-all duration-1000 w-3/4"></div>
			</div>
			
			<!-- Pulsing dots -->
			<div class="flex justify-center space-x-2 mt-6">
				<span class="w-3 h-3 bg-white rounded-full animate-bounce"></span>
				<span class="w-3 h-3 bg-white rounded-full animate-bounce delay-100"></span>
				<span class="w-3 h-3 bg-white rounded-full animate-bounce delay-200"></span>
			</div>
		</div>
	</div>

	<!-- Fun facts at the bottom -->
	<div class="absolute bottom-12 left-1/2 transform -translate-x-1/2 bg-white/10 backdrop-blur-lg rounded-2xl border border-white/20 p-6 text-center text-white max-w-md mx-4">
		<h3 class="text-lg font-bold mb-3">💡 What We're Learning</h3>
		<div class="space-y-2 text-sm">
			<div class="animate-pulse">🌍 Pure Tailwind CSS - no custom CSS needed!</div>
			<div class="animate-pulse delay-300">🎨 Built-in animations: animate-spin, animate-bounce</div>
			<div class="animate-pulse delay-500">⚡ Gradient backgrounds and transparency effects</div>
			<div class="animate-pulse delay-700">📱 Responsive design with absolute positioning</div>
		</div>
	</div>

	<!-- Learning notes for mobile -->
	<div class="hidden md:block absolute top-1/2 left-8 transform -translate-y-1/2 bg-black/20 backdrop-blur-sm rounded-lg p-4 text-white text-xs max-w-xs">
		<h4 class="font-bold mb-2">🎓 Tailwind Classes Used:</h4>
		<ul class="space-y-1 text-xs">
			<li>• <code class="bg-white/20 px-1 rounded">bg-gradient-to-br</code> - Gradient background</li>
			<li>• <code class="bg-white/20 px-1 rounded">animate-spin</code> - Rotating animation</li>
			<li>• <code class="bg-white/20 px-1 rounded">absolute inset-0</code> - Full positioning</li>
			<li>• <code class="bg-white/20 px-1 rounded">backdrop-blur-lg</code> - Glass effect</li>
		</ul>
	</div>

	<!-- More learning notes on the right -->
	<div class="hidden md:block absolute top-1/2 right-8 transform -translate-y-1/2 bg-black/20 backdrop-blur-sm rounded-lg p-4 text-white text-xs max-w-xs">
		<h4 class="font-bold mb-2">🎯 Animation Classes:</h4>
		<ul class="space-y-1 text-xs">
			<li>• <code class="bg-white/20 px-1 rounded">animate-pulse</code> - Smooth fading</li>
			<li>• <code class="bg-white/20 px-1 rounded">animate-bounce</code> - Bouncing dots</li>
			<li>• <code class="bg-white/20 px-1 rounded">animate-ping</code> - Expanding circles</li>
			<li>• <code class="bg-white/20 px-1 rounded">delay-100</code> - Animation timing</li>
		</ul>
	</div>
</div>
