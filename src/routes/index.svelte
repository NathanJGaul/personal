<script>
    import { faEnvelope } from '@fortawesome/free-solid-svg-icons';
	import { faGithub, faTwitter, faLinkedin } from '@fortawesome/free-brands-svg-icons';
	import SocialIcon from '$lib/components/SocialIcon.svelte';
</script>

<section class="text-gray-600 body-font">
	<div class="min-w-screen min-h-screen flex flex-col justify-center items-center">
		<div class="w-fit flex flex-col items-center p-10 rounded-3xl bg-slate-500/40">
			<h1 class="title-font text-6xl mb-4 font-medium text-slate-200">Nathan Gaul</h1>
			<h3 class="text-xl font-normal text-slate-300">Developer | Web Designer | Entrepreneur</h3>
			<span class="inline-flex lg:ml-auto mt-6 w-full justify-center">
				<SocialIcon icon={faGithub} url="https://github.com/NathanJGaul" />
                <SocialIcon icon={faTwitter} url="https://twitter.com/NathanJGaul" />
                <SocialIcon icon={faLinkedin} url="https://www.linkedin.com/in/nathanjgaul/" />
                <SocialIcon icon={faEnvelope} url="mailto:nathanjgaul@gmail.com" />
			</span>
		</div>
	</div>
</section>
