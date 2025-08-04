<script>
	import { onMount } from 'svelte';
	
	let mounted = false;
	let skillsVisible = false;
	
	onMount(() => {
		mounted = true;
		// Trigger skills animation after a delay
		setTimeout(() => {
			skillsVisible = true;
		}, 1000);
	});
</script>

<div class="min-h-screen bg-gradient-to-br from-indigo-900 via-purple-900 to-pink-900 relative overflow-hidden">
	<!-- Animated Background Elements -->
	<div class="absolute inset-0 overflow-hidden">
		<div class="absolute top-20 left-10 w-2 h-2 bg-white rounded-full animate-pulse opacity-70"></div>
		<div class="absolute top-40 right-20 w-1 h-1 bg-blue-300 rounded-full animate-ping"></div>
		<div class="absolute bottom-32 left-1/4 w-1 h-1 bg-pink-300 rounded-full animate-pulse delay-200"></div>
		<div class="absolute top-60 right-1/3 w-2 h-2 bg-purple-300 rounded-full animate-ping delay-500"></div>
		<div class="absolute bottom-20 right-10 w-1 h-1 bg-cyan-300 rounded-full animate-pulse delay-700"></div>
	</div>

	<!-- Main Content -->
	<div class="relative z-10 max-w-6xl mx-auto px-6 py-12">
		
		<!-- Hero Section with Profile -->
		<div class="text-center mb-16">
			<div class="relative inline-block group">
				<!-- Glowing ring around profile picture -->
				<div class="absolute inset-0 bg-gradient-to-r from-blue-400 via-purple-400 to-pink-400 rounded-full blur-lg opacity-75 group-hover:opacity-100 transition-opacity duration-300 animate-pulse"></div>
				
				<img
					src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=200&h=200&fit=crop&crop=face"
					alt="Alex Chen"
					class="relative w-48 h-48 rounded-full object-cover border-4 border-white shadow-2xl transform transition-transform duration-300 group-hover:scale-105"
					class:animate-fade-in={mounted}
				/>
			</div>
			
			<h1 class="text-6xl font-bold text-white mt-8 mb-4 drop-shadow-lg" class:animate-slide-up={mounted}>
				Alex Chen
			</h1>
			<div class="text-xl text-blue-200 mb-2" class:animate-slide-up={mounted}>
				🎓 Grade 10 • Lincoln High School
			</div>
			<div class="text-lg text-purple-200" class:animate-slide-up={mounted}>
				Future Software Engineer 🚀
			</div>
		</div>

		<!-- Animated Cards Grid -->
		<div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 mb-16">
			
			<!-- About Me Card -->
			<div class="group relative p-8 bg-white/10 backdrop-blur-lg rounded-2xl border border-white/20 shadow-xl hover:shadow-2xl transform hover:scale-105 transition-all duration-300" class:animate-fade-in-up={mounted}>
				<div class="absolute inset-0 bg-gradient-to-r from-blue-500/20 to-purple-500/20 rounded-2xl opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
				<div class="relative z-10">
					<h3 class="text-2xl font-bold text-white mb-4 flex items-center">
						<span class="text-3xl mr-3">👋</span>
						About Me
					</h3>
					<p class="text-gray-200 leading-relaxed">
						Hi there! I'm Alex, a passionate 10th grader who loves technology, sports, and creative writing. 
						I dream of becoming a software engineer and building amazing things that help people!
					</p>
				</div>
			</div>

			<!-- Interests Card -->
			<div class="group relative p-8 bg-white/10 backdrop-blur-lg rounded-2xl border border-white/20 shadow-xl hover:shadow-2xl transform hover:scale-105 transition-all duration-300" class:animate-fade-in-up={mounted}>
				<div class="absolute inset-0 bg-gradient-to-r from-green-500/20 to-cyan-500/20 rounded-2xl opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
				<div class="relative z-10">
					<h3 class="text-2xl font-bold text-white mb-4 flex items-center">
						<span class="text-3xl mr-3">🎯</span>
						Interests
					</h3>
					<div class="space-y-3">
						<div class="flex items-center text-gray-200 hover:text-white transition-colors">
							<span class="text-xl mr-3">🎮</span>
							<span>Game Development</span>
						</div>
						<div class="flex items-center text-gray-200 hover:text-white transition-colors">
							<span class="text-xl mr-3">🏀</span>
							<span>Basketball</span>
						</div>
						<div class="flex items-center text-gray-200 hover:text-white transition-colors">
							<span class="text-xl mr-3">📚</span>
							<span>Sci-Fi Books</span>
						</div>
						<div class="flex items-center text-gray-200 hover:text-white transition-colors">
							<span class="text-xl mr-3">🎵</span>
							<span>Guitar Playing</span>
						</div>
					</div>
				</div>
			</div>

			<!-- Goals Card -->
			<div class="group relative p-8 bg-white/10 backdrop-blur-lg rounded-2xl border border-white/20 shadow-xl hover:shadow-2xl transform hover:scale-105 transition-all duration-300" class:animate-fade-in-up={mounted}>
				<div class="absolute inset-0 bg-gradient-to-r from-pink-500/20 to-orange-500/20 rounded-2xl opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
				<div class="relative z-10">
					<h3 class="text-2xl font-bold text-white mb-4 flex items-center">
						<span class="text-3xl mr-3">🎯</span>
						Goals
					</h3>
					<div class="space-y-3">
						<div class="flex items-center text-gray-200 hover:text-white transition-colors">
							<span class="text-xl mr-3">📱</span>
							<span>Build my first app</span>
						</div>
						<div class="flex items-center text-gray-200 hover:text-white transition-colors">
							<span class="text-xl mr-3">🏆</span>
							<span>Make varsity team</span>
						</div>
						<div class="flex items-center text-gray-200 hover:text-white transition-colors">
							<span class="text-xl mr-3">⚛️</span>
							<span>Learn React</span>
						</div>
						<div class="flex items-center text-gray-200 hover:text-white transition-colors">
							<span class="text-xl mr-3">✍️</span>
							<span>Start coding blog</span>
						</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Skills Section with Animated Bars -->
		<div class="mb-16">
			<h2 class="text-4xl font-bold text-white text-center mb-12">
				<span class="bg-gradient-to-r from-blue-400 to-purple-400 bg-clip-text text-transparent">
					My Skills
				</span>
			</h2>
			
			<div class="grid md:grid-cols-2 gap-8">
				<div class="space-y-6">
					<!-- Python Skill -->
					<div class="skill-item">
						<div class="flex justify-between text-white mb-2">
							<span class="font-semibold">🐍 Python</span>
							<span>85%</span>
						</div>
						<div class="w-full bg-white/20 rounded-full h-3">
							<div 
								class="bg-gradient-to-r from-green-400 to-blue-500 h-3 rounded-full transition-all duration-1000 ease-out"
								class:w-[85%]={skillsVisible}
								class:w-0={!skillsVisible}
							></div>
						</div>
					</div>

					<!-- JavaScript Skill -->
					<div class="skill-item">
						<div class="flex justify-between text-white mb-2">
							<span class="font-semibold">⚡ JavaScript</span>
							<span>70%</span>
						</div>
						<div class="w-full bg-white/20 rounded-full h-3">
							<div 
								class="bg-gradient-to-r from-yellow-400 to-orange-500 h-3 rounded-full transition-all duration-1000 ease-out delay-200"
								class:w-[70%]={skillsVisible}
								class:w-0={!skillsVisible}
							></div>
						</div>
					</div>

					<!-- HTML/CSS Skill -->
					<div class="skill-item">
						<div class="flex justify-between text-white mb-2">
							<span class="font-semibold">🎨 HTML/CSS</span>
							<span>90%</span>
						</div>
						<div class="w-full bg-white/20 rounded-full h-3">
							<div 
								class="bg-gradient-to-r from-pink-400 to-red-500 h-3 rounded-full transition-all duration-1000 ease-out delay-400"
								class:w-[90%]={skillsVisible}
								class:w-0={!skillsVisible}
							></div>
						</div>
					</div>
				</div>

				<div class="space-y-6">
					<!-- Basketball Skill -->
					<div class="skill-item">
						<div class="flex justify-between text-white mb-2">
							<span class="font-semibold">🏀 Basketball</span>
							<span>80%</span>
						</div>
						<div class="w-full bg-white/20 rounded-full h-3">
							<div 
								class="bg-gradient-to-r from-orange-400 to-red-500 h-3 rounded-full transition-all duration-1000 ease-out delay-600"
								class:w-[80%]={skillsVisible}
								class:w-0={!skillsVisible}
							></div>
						</div>
					</div>

					<!-- Creative Writing Skill -->
					<div class="skill-item">
						<div class="flex justify-between text-white mb-2">
							<span class="font-semibold">✍️ Writing</span>
							<span>75%</span>
						</div>
						<div class="w-full bg-white/20 rounded-full h-3">
							<div 
								class="bg-gradient-to-r from-purple-400 to-pink-500 h-3 rounded-full transition-all duration-1000 ease-out delay-800"
								class:w-[75%]={skillsVisible}
								class:w-0={!skillsVisible}
							></div>
						</div>
					</div>

					<!-- Guitar Skill -->
					<div class="skill-item">
						<div class="flex justify-between text-white mb-2">
							<span class="font-semibold">🎸 Guitar</span>
							<span>60%</span>
						</div>
						<div class="w-full bg-white/20 rounded-full h-3">
							<div 
								class="bg-gradient-to-r from-cyan-400 to-blue-500 h-3 rounded-full transition-all duration-1000 ease-out delay-1000"
								class:w-[60%]={skillsVisible}
								class:w-0={!skillsVisible}
							></div>
						</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Project Showcase -->
		<div class="mb-16">
			<h2 class="text-4xl font-bold text-white text-center mb-12">
				<span class="bg-gradient-to-r from-green-400 to-cyan-400 bg-clip-text text-transparent">
					My Projects
				</span>
			</h2>
			
			<div class="grid md:grid-cols-2 gap-8">
				<div class="group relative overflow-hidden rounded-2xl shadow-2xl transform hover:scale-105 transition-all duration-300">
					<img
						src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?w=400&h=250&fit=crop"
						alt="Portfolio website project"
						class="w-full h-64 object-cover group-hover:scale-110 transition-transform duration-300"
					/>
					<div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
					<div class="absolute bottom-0 left-0 right-0 p-6 text-white">
						<h3 class="text-xl font-bold mb-2">🌐 Portfolio Website</h3>
						<p class="text-sm text-gray-200">My first responsive website built with HTML, CSS, and JavaScript</p>
					</div>
				</div>

				<div class="group relative overflow-hidden rounded-2xl shadow-2xl transform hover:scale-105 transition-all duration-300">
					<img
						src="https://images.unsplash.com/photo-1518709268805-4e9042af2176?w=400&h=250&fit=crop"
						alt="Basketball app project"
						class="w-full h-64 object-cover group-hover:scale-110 transition-transform duration-300"
					/>
					<div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent"></div>
					<div class="absolute bottom-0 left-0 right-0 p-6 text-white">
						<h3 class="text-xl font-bold mb-2">🏀 Basketball Stats App</h3>
						<p class="text-sm text-gray-200">Python app to track basketball statistics and game performance</p>
					</div>
				</div>
			</div>
		</div>

		<!-- Contact Section -->
		<div class="text-center">
			<h2 class="text-4xl font-bold text-white mb-8">
				<span class="bg-gradient-to-r from-pink-400 to-purple-400 bg-clip-text text-transparent">
					Let's Connect! 🚀
				</span>
			</h2>
			
			<div class="flex flex-wrap justify-center gap-6">
				<button class="group relative px-8 py-4 bg-gradient-to-r from-blue-500 to-purple-600 rounded-full text-white font-semibold shadow-lg hover:shadow-2xl transform hover:scale-105 transition-all duration-300">
					<span class="relative z-10 flex items-center">
						<span class="text-xl mr-2">📧</span>
						Email Me
					</span>
					<div class="absolute inset-0 bg-gradient-to-r from-purple-600 to-pink-600 rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
				</button>
				
				<button class="group relative px-8 py-4 bg-gradient-to-r from-green-500 to-cyan-600 rounded-full text-white font-semibold shadow-lg hover:shadow-2xl transform hover:scale-105 transition-all duration-300">
					<span class="relative z-10 flex items-center">
						<span class="text-xl mr-2">💻</span>
						GitHub
					</span>
					<div class="absolute inset-0 bg-gradient-to-r from-cyan-600 to-blue-600 rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
				</button>
				
				<button class="group relative px-8 py-4 bg-gradient-to-r from-pink-500 to-red-600 rounded-full text-white font-semibold shadow-lg hover:shadow-2xl transform hover:scale-105 transition-all duration-300">
					<span class="relative z-10 flex items-center">
						<span class="text-xl mr-2">📱</span>
						Discord
					</span>
					<div class="absolute inset-0 bg-gradient-to-r from-red-600 to-orange-600 rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div>
				</button>
			</div>
		</div>

		<!-- Fun Quote -->
		<div class="mt-16 text-center">
			<div class="relative inline-block p-8 bg-white/5 backdrop-blur-lg rounded-2xl border border-white/10">
				<div class="absolute top-4 left-4 text-4xl text-blue-400 opacity-50">"</div>
				<p class="text-xl text-white italic mb-4 px-8">
					The best way to predict the future is to create it.
				</p>
				<p class="text-gray-300">- Peter Drucker</p>
				<div class="absolute bottom-4 right-4 text-4xl text-blue-400 opacity-50 rotate-180">"</div>
			</div>
		</div>
	</div>
</div>

<style>
	@keyframes fade-in {
		from { opacity: 0; }
		to { opacity: 1; }
	}
	
	@keyframes slide-up {
		from { 
			opacity: 0; 
			transform: translateY(30px); 
		}
		to { 
			opacity: 1; 
			transform: translateY(0); 
		}
	}
	
	@keyframes fade-in-up {
		from { 
			opacity: 0; 
			transform: translateY(50px); 
		}
		to { 
			opacity: 1; 
			transform: translateY(0); 
		}
	}
	
	.animate-fade-in {
		animation: fade-in 1s ease-out;
	}
	
	.animate-slide-up {
		animation: slide-up 0.8s ease-out;
	}
	
	.animate-fade-in-up {
		animation: fade-in-up 0.8s ease-out;
	}
</style>
