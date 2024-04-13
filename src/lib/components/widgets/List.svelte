<script>
	import ListItem from './../UI/List_item.svelte';

</script>

<div class="List">
    <ListItem/>
    <ListItem/>
    <ListItem/>
    <ListItem/>
    <ListItem/>
    <ListItem/>
    <ListItem/>
</div>

<style>
    .List {
        display: flex;
        flex-wrap: wrap;
        margin-top: 20px;
        margin-right: 10px;
        margin-left: 10px;
        gap: 41px;
        justify-content: center;
    }

    @media (max-width: 480px) {
        .List {
            gap: 10px;
            justify-content: center;
            
        }
    }
</style>