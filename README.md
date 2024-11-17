<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com?plugins=forms,typography"></script>
		<script src="https://unpkg.com/unlazy@0.11.3/dist/unlazy.with-hashing.iife.js" defer init></script>
		<script type="text/javascript">
			window.tailwind.config = {
				darkMode: ['class'],
				theme: {
					extend: {
						colors: {
							border: 'hsl(var(--border))',
							input: 'hsl(var(--input))',
							ring: 'hsl(var(--ring))',
							background: 'hsl(var(--background))',
							foreground: 'hsl(var(--foreground))',
							primary: {
								DEFAULT: 'hsl(var(--primary))',
								foreground: 'hsl(var(--primary-foreground))'
							},
							secondary: {
								DEFAULT: 'hsl(var(--secondary))',
								foreground: 'hsl(var(--secondary-foreground))'
							},
							destructive: {
								DEFAULT: 'hsl(var(--destructive))',
								foreground: 'hsl(var(--destructive-foreground))'
							},
							muted: {
								DEFAULT: 'hsl(var(--muted))',
								foreground: 'hsl(var(--muted-foreground))'
							},
							accent: {
								DEFAULT: 'hsl(var(--accent))',
								foreground: 'hsl(var(--accent-foreground))'
							},
							popover: {
								DEFAULT: 'hsl(var(--popover))',
								foreground: 'hsl(var(--popover-foreground))'
							},
							card: {
								DEFAULT: 'hsl(var(--card))',
								foreground: 'hsl(var(--card-foreground))'
							},
						},
					}
				}
			}
		</script>
		<style type="text/tailwindcss">
			@layer base {
				:root {
					--background: 0 0% 100%;
--foreground: 240 10% 3.9%;
--card: 0 0% 100%;
--card-foreground: 240 10% 3.9%;
--popover: 0 0% 100%;
--popover-foreground: 240 10% 3.9%;
--primary: 240 5.9% 10%;
--primary-foreground: 0 0% 98%;
--secondary: 240 4.8% 95.9%;
--secondary-foreground: 240 5.9% 10%;
--muted: 240 4.8% 95.9%;
--muted-foreground: 240 3.8% 46.1%;
--accent: 240 4.8% 95.9%;
--accent-foreground: 240 5.9% 10%;
--destructive: 0 84.2% 60.2%;
--destructive-foreground: 0 0% 98%;
--border: 240 5.9% 90%;
--input: 240 5.9% 90%;
--ring: 240 5.9% 10%;
--radius: 0.5rem;
				}
				.dark {
					--background: 240 10% 3.9%;
--foreground: 0 0% 98%;
--card: 240 10% 3.9%;
--card-foreground: 0 0% 98%;
--popover: 240 10% 3.9%;
--popover-foreground: 0 0% 98%;
--primary: 0 0% 98%;
--primary-foreground: 240 5.9% 10%;
--secondary: 240 3.7% 15.9%;
--secondary-foreground: 0 0% 98%;
--muted: 240 3.7% 15.9%;
--muted-foreground: 240 5% 64.9%;
--accent: 240 3.7% 15.9%;
--accent-foreground: 0 0% 98%;
--destructive: 0 62.8% 30.6%;
--destructive-foreground: 0 0% 98%;
--border: 240 3.7% 15.9%;
--input: 240 3.7% 15.9%;
--ring: 240 4.9% 83.9%;
				}
			}
		</style>
  </head>
  <body>
    

<div class="bg-black text-white">
  <header class="flex justify-between items-center p-4">
    <div class="flex items-center">
      
      <h1 class="text-3xl font-bold ml-2">
        <span class="to-blackext-white">sr</span>
        <span class="text-pink-500">squ</span>
        <span class="text-cyan-400">irt</span>
      </h1>
    </div>
    <nav class="flex space-x-4">
      <a href="#" class="font-bold text-lg">Inicio</a>
      <a href="#" class="font-bold text-lg">Contenido VIP</a>
    </nav>
  </header>
  <div class="bg-pink-500 to-blackext-white text-center p-2">
    <p class="font-bold text-lg">Oferta de contenido premium por $10.99/mes</p>
  </div>
  <main class="p-4 bg-black">
    <div class="grid grid-cols-2 gap-4">
      <div class="bg-zinc-800 p-4 rounded-lg">
        <h2 class="text-white">lenidolicastle</h2>
        <video class="w-full" controls>
          <source src="video5145752793524470967.mp4" type="video/mp4" />
          Your browser does not support the video tag.
        </video>
        <p class="text-white">6k Me gusta</p>
        <p class="text-white">88k Vistas</p>
      </div>
      <div class="bg-zinc-800 p-4 rounded-lg">
        <h2 class="text-white">Título del Video 2</h2>
        <video class="w-full" controls>
          <source src="video2.mp4" type="video/mp4" />
          Your browser does not support the video tag.
        </video>
        <p class="text-white">3k Me gusta</p>
        <p class="text-white">110k Vistas</p>
      </div>
      <div class="bg-zinc-800 p-4 rounded-lg">
        <h2 class="text-white">Título del Video 3</h2>
        <video class="w-full" controls>
          <source src="video3.mp4" type="video/mp4" />
          Your browser does not support the video tag.
        </video>
        <p class="text-white">5k Me gusta</p>
        <p class="text-white">100k Vistas</p>
      </div>
      <div class="bg-zinc-800 p-4 rounded-lg">
        <h2 class="text-white">Título del Video 4</h2>
        <video class="w-full" controls>
          <source src="video4.mp4" type="video/mp4" />
          Your browser does not support the video tag.
        </video>
        <p class="text-white">8k Me gusta</p>
        <p class="text-white">156k Vistas</p>
      </div>
    </div>
  </main>
</div>


  </body>
</html>


