<script lang="ts">
	export let src: string;
	export let text: string;
    export let href: string
</script>

<div class="component">
	<img {src} alt=""/>
	<a class="text" href={href}>{text} </a>
</div>

<style>

@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
    .component {
        display: flex;
        align-items: center;
        justify-content: center;
        border: 1px solid #E7E7E7;
        padding: 5px;

    }
    .text {
        margin: 20px;
        font-size: 25px;
        font-family: "Roboto", sans-serif;
        font-weight: 400;
        font-style: normal;
        text-decoration: none;
        color: #000;
}

@media (max-width: 480px) {
    .component {
        height: 120px;
    }
    .text {
        font-size: 25px;
    }
}
</style>
