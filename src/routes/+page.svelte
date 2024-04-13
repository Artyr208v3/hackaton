<script lang="ts">
	import Header from './../lib/components/widgets/header.svelte';
	import Main from '$lib/components/widgets/main.svelte';
	import Footer from '$lib/components/widgets/footer.svelte';

    let source: string = "/logo.png"
</script>

<Header source={source}/>
<Main/>
<Footer/>

