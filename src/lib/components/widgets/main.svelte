<script>
	import Title from "../UI/title.svelte";

</script>



<main>
<Title/>
<img src="Пёс-космос.png" alt="">

</main>

<style>
    main {
        height: 600px;
        display: flex;
        align-items: center;
        justify-content: space-around;
    }
    img {
        width: 528px;
        height: 385px;
    }

    @media (max-width: 480px) {
        main {
            display: flex;
            flex-direction: column;
        }
        img {
            width: 300px;
            height: 200px;
        }

    }

</style>