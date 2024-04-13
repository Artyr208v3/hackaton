<div class="List_item">
    <p class="Work">Название работы</p>
    <img src="/Work.png" alt="">
    <p>Фамилия Имя участника</p>

    <button class="wt_btn">Подробнее</button>
</div>

<style>
    img {
        padding-left: 5px;
        padding-right: 5px;
        width: 220px;
        height: 200px;
    }
    .List_item {
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 250px;
        height: 353px;
        border: 1px solid #e7e7e7;
        border-radius: 10px;
}
.Work {
    text-align: left;
}
.wt_btn {
    background-color: #d5fc53;
    color: #ffffff;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid #e7e7e7;
    width: 230px;
    height: 30px;
}

@media (max-width: 480px) {
    .List_item {
        width: 100%;
        height: auto;
        padding: 15px;
        border-radius: 10px;
    }

    img {
        width: 100%;

    }
}
</style>