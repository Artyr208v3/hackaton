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
        text-align:center;
        font-size: 25px;
        font-weight: 500px;
    }
@media (max-width:480px) {
p {text-align:left;}
}
</style>
