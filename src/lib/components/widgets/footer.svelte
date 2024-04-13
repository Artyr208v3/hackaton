<script lang="ts">
import FooterItem from './../UI/footer_item.svelte';

let props1 = {
    src : "/Лупа.png",
    text : "Подробнее о празднике",
    href : `/About`
}

let props2 = {
    src : "/Заявка.png",
    text : "Подать заявку",
    href : "/Auth"
}

let props3 = {
    src : "/Вопрос.svg",
    text : "Заявки",
    href : "/List"
}

</script>


<footer>
    <div class="component">
        <span class="text">Привнести свой вклад</span>
        <img src="/Arrow 1.svg" alt="">
    </div>
    <FooterItem {...props1}/>
    <FooterItem {...props2}/>
    <FooterItem {...props3}/>
</footer>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
    footer {
        display: grid;
        grid-template-columns: 25% 25% 25% 25%;
        border: 1px solid #E7E7E7;
    }
    .text {
        margin: 20px;
        font-size: 25px;
        font-family: "Roboto", sans-serif;
        font-weight: 400;
        font-style: normal;
}
.component {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        border: 1px solid #E7E7E7;
        padding: 5px;

    }

    @media (max-width: 480px) {
        footer {
            display: flex;
            flex-direction: column;
        }
        .component {
            height: 120px;
        }
        .text {
            font-size: 20px;
        }
    }
</style>