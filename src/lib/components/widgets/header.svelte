<script lang="ts">
	import MenuButton from "../UI/menu_button.svelte";
	import UserBtn from "../UI/user_btn.svelte";
    export let source: string
</script>
<header>
    <MenuButton/>
    <img src={source} alt="">
    <UserBtn/>
</header>

<style>
    header {
        width: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 110px;
        border-bottom: 1px solid #E7E7E7;
        padding-bottom: 5px;
}
@media (max-width: 480px) {
    header {
        height: 80px;
        padding-bottom: 0;
        border-bottom: none;
        border-top: 1px solid #E7E7E7;
    }
}
</style>