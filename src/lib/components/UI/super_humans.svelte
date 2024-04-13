<script>
	import HumansAlbum from './humans_album.svelte';

</script>

<div class="super_humans">
    <p class="author_name">Главные люди</p>
    <HumansAlbum/>
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
    .super_humans {
        display: flex;
        flex-direction: column;
        align-items: center;
        border: 1px solid #E7E7E7;
        border-right: none;
        border-bottom: none;
    }
    .author_name {
        font-family: 'Roboto', sans-serif;
		font-weight: 400;
		font-style: normal;
        border: 1px solid #E7E7E7;
        border-top: none;
        font-size: 18px;
        margin: 0;
        border-radius: 0 0 10px 10px;
        padding: 2px 30px 2px 30px;
        margin-bottom: 20px;
        
    }
</style>