<script lang="ts">
	import MainAbout from './../../lib/components/widgets/main_about.svelte';
	import Header from '$lib/components/widgets/header.svelte';

    let source: string = "/logo.png"
    </script>

<Header source={source}/>
<MainAbout/>

<style>

</style>