<div class="humans_album">
    <img src="/human1.png" alt="">
    <img src="/human2.png" alt="">
    <img src="/human3.png" alt="">
    <img src="/human4.png" alt="">
    <img src="/image 11.png" alt="">
    <img src="/human6.png" alt="">
    <img src="/human7.png" alt="">
    <img src="/human8.png" alt="">
    <img src="/human9.png" alt="">
    <img src="/human10.png" alt="">
</div>

<style>
    img {
        margin: 0;
        padding: 0;
    }
    .humans_album {
        margin: 0;
        padding: 0;
        display: grid;
        gap: 17px;
        grid-template-columns: repeat(5, 100px);
    }

    @media (max-width: 480px) {
        .humans_album {
            grid-template-columns: repeat(3, 100px);
        }
        img {
            width: 100px;
        }
    }
</style>