<script>
	import '../app.css';
    import background from '$lib/images/background.jpg';
</script>

<div
    id="background" 
    class="bg-no-repeat bg-cover bg-center"
    style="background-image: url({background})">
    <slot />
</div>