<script context="module" lang="ts">
</script>

<svelte:head>
	<link
		href="https://fonts.googleapis.com/css2?family=Work+Sans:ital,wght@0,200;0,400;1,400;1,700;1,900&display=swap"
		rel="stylesheet"
	/>
	<link
		rel="stylesheet"
		href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css"
	/>
	<link
		rel="stylesheet"
		href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
		integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
		crossorigin="anonymous"
		referrerpolicy="no-referrer"
	/>
</svelte:head>

<main class="flex h-screen p-10 antialiased">
	<header
		class="header-container m-auto p-2 lg:p-4 flex flex-col md:flex-row border-double border-4 border-white rounded-lg backdrop-blur-md"
	>
		<div class="text-white px-4 md:pt-0 max-w-2xl">
			<h1 class="title text-4xl md:text-5xl w-full">Hi there,</h1>
			<h1 class="title text-4xl md:text-5xl w-full">I'm Brandon (opti)!</h1>
			<p class="text-2xl font-extralight py-4 max-w-lg">
				Just a normal everyday full stack dev who enjoys programming and building cool things.
			</p>

			<div class="contact flex flex-row gap-2 text-2xl">
				<a
					href="https://github.com/opti21"
					target="blank"
					class="discord font-extralight hover:underline"
					>Github <i class="devicon-github-original" /></a
				>
				<a
					href="https://twitter.com/opti21_"
					class="twitter font-extralight hover:underline"
					target="blank">Twitter <i class="fa-brands fa-twitter" /></a
				>
			</div>

			<!-- <div class="border-white border-double border-t-4 my-2" /> -->
			<div class="pt-6">
				<h2 class="text-2xl">My Tech Stack:</h2>
				<div class="text-4xl">
					<i class="devicon-go-original-wordmark" />
					<i class="devicon-nodejs-plain" />
					<i class="devicon-javascript-plain" />
					<i class="devicon-nextjs-original" />
					<i class="devicon-react-original" />
					<i class="devicon-html5-plain" />
					<i class="devicon-tailwindcss-plain" />
					<i class="devicon-vuejs-plain" />
					<i class="devicon-svelte-plain" />
					<i class="devicon-mongodb-plain" />
					<i class="devicon-postgresql-plain" />
				</div>
			</div>
			<div class="projects mt-4">
				<h2 class="text-2xl">Projects coming soon</h2>
			</div>
		</div>
		<div
			class="header-content-right text-white md:border-white md:border-double md:border-l-4 pt-2 md:px-2 md:pt-0 flex items-center"
		>
			<img
				class="header-image border border-white rounded-md mx-auto"
				src="/gopher_pfp.jpg"
				alt="profile of brandon as a gopher"
				width="300"
				height="300"
			/>
		</div>
	</header>

	<div class="background">
		<span class="bg-text-left">
			<i class="devicon-go-original-wordmark" />
			<i class="devicon-nodejs-plain" />
			<i class="devicon-javascript-plain" />
			<i class="devicon-react-original" />
			<i class="devicon-html5-plain" />
			<i class="devicon-tailwindcss-plain" />
			<i class="devicon-vuejs-plain" />
			<i class="devicon-svelte-plain" />
			<i class="devicon-nextjs-original" />
			<i class="devicon-mongodb-plain" />
			<i class="devicon-postgresql-plain" />
			<i class="devicon-go-original-wordmark" />
			<i class="devicon-nodejs-plain" />
			<i class="devicon-javascript-plain" />
			<i class="devicon-react-original" />
			<i class="devicon-html5-plain" />
			<i class="devicon-tailwindcss-plain" />
			<i class="devicon-vuejs-plain" />
			<i class="devicon-svelte-plain" />
			<i class="devicon-nextjs-original" />
			<i class="devicon-mongodb-plain" />
			<i class="devicon-postgresql-plain" />
		</span>
		<span class="bg-text-right"> FULL STACK FULL STACK FULL STACK FULL STACK FULL STACK</span>
		<span class="bg-text-left">
			<i class="devicon-go-original-wordmark" />
			<i class="devicon-nodejs-plain" />
			<i class="devicon-javascript-plain" />
			<i class="devicon-react-original" />
			<i class="devicon-html5-plain" />
			<i class="devicon-tailwindcss-plain" />
			<i class="devicon-vuejs-plain" />
			<i class="devicon-svelte-plain" />
			<i class="devicon-nextjs-original" />
			<i class="devicon-mongodb-plain" />
			<i class="devicon-postgresql-plain" />
			<i class="devicon-go-original-wordmark" />
			<i class="devicon-nodejs-plain" />
			<i class="devicon-javascript-plain" />
			<i class="devicon-react-original" />
			<i class="devicon-html5-plain" />
			<i class="devicon-tailwindcss-plain" />
			<i class="devicon-vuejs-plain" />
			<i class="devicon-svelte-plain" />
			<i class="devicon-nextjs-original" />
			<i class="devicon-mongodb-plain" />
			<i class="devicon-postgresql-plain" />
		</span>
		<span class="bg-text-right"> FULL STACK FULL STACK FULL STACK FULL STACK FULL STACK</span>
	</div>
</main>

<style>
	:global(body) {
		background-color: #01002d;
	}

	.background {
		position: absolute;
		left: 0px;
		top: 0px;
		width: 100%;
		z-index: -1;
		overflow: hidden;
		color: rgb(255, 255, 255);
	}

	.background:after {
		animation: grain 8s steps(10) infinite;
		background-image: url('/noise-transparent.png');
		content: '';
		height: 300%;
		left: -50%;
		opacity: 0.5;
		position: fixed;
		top: -100%;
		width: 300%;
	}

	@keyframes grain {
		0% {
			transform: translate(0, 0);
		}
		10% {
			transform: translate(-5%, -5%);
		}
		20% {
			transform: translate(-10%, 5%);
		}
		30% {
			transform: translate(5%, -10%);
		}
		40% {
			transform: translate(-5%, 15%);
		}
		50% {
			transform: translate(-10%, 5%);
		}
		60% {
			transform: translate(15%, 0);
		}
		70% {
			transform: translate(0, 10%);
		}
		80% {
			transform: translate(-15%, 0);
		}
		90% {
			transform: translate(10%, 5%);
		}
		100% {
			transform: translate(5%, 0);
		}
	}

	.bg-text-left {
		font-family: 'Work Sans', sans-serif;
		font-weight: 900;
		font-style: italic;
		position: relative;
		display: block;
		font-size: 240px;
		line-height: 229px;
		/* letter-spacing: 0.24em; */
		white-space: nowrap;
		color: rgb(253, 252, 251);
		width: max-content;
		text-shadow: rgb(190, 241, 241) -2px -2px 0px, rgb(190, 241, 241) 2px -2px 0px,
			rgb(16, 17, 13) -2px 2px 0px, rgb(16, 17, 13) 2px 2px 0px;
		opacity: 0.1;
		animation: 120s linear 0s infinite normal none running marquee;
		will-change: transform;
		/* font-weight: 800; */
		margin-left: -400px;
	}

	.bg-text-right {
		font-family: 'Work Sans', sans-serif;
		font-weight: 900;
		font-style: italic;
		position: relative;
		display: block;
		font-size: 240px;
		line-height: 229px;
		/* letter-spacing: 0.24em; */
		white-space: nowrap;
		color: rgb(253, 252, 251);
		width: max-content;
		text-shadow: rgb(16, 17, 13) -2px -2px 0px, rgb(16, 17, 13) 2px -2px 0px,
			rgb(16, 17, 13) -2px 2px 0px, rgb(16, 17, 13) 2px 2px 0px;
		opacity: 0.1;
		animation: 120s linear 0s infinite reverse none running marquee;
		will-change: transform;
		font-weight: 800;
		margin-left: -400px;
	}

	.header-image {
		box-shadow: 0 0 3px 0 rgb(255 255 255);
	}

	.title {
		font-family: 'Work Sans', sans-serif;
		font-weight: 700;
		font-style: italic;
	}

	.header-content-right {
		font-family: 'Work Sans', sans-serif;
	}

	@keyframes marquee {
		0% {
			transform: translateX(0px);
		}
		100% {
			transform: translate3d(-50%, 0px, 0px);
		}
	}
</style>
