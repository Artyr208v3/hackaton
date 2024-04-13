<script lang="ts">
import FormReg from '$lib/components/widgets/form_reg.svelte';
import Header from '$lib/components/widgets/header.svelte';

    let source: string = "/logo.png"
    </script>

<Header source={source}/>
<p>Общая информация</p>
<FormReg/>

<style>
    p {
        text-align:left;
        font-size: 25px;
        font-weight: 500px;
    }
</style>