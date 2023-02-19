<script>
	import '../app.postcss';
    import '../app.css';
</script>

<div class="page_wrapper">
	<slot />
</div>

<style>
	.page_wrapper {
		height: 100%;
		width: 100%;
        background-color: blanchedalmond;
        flex-grow: 1;
	}
</style>
