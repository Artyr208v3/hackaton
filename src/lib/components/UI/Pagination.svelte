<div class="pagination">
    <div class="arrow_left"><svg width="13" height="22" viewBox="0 0 13 22" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M13 3.14286L4.875 11L13 18.8571L11.375 22L-4.79876e-07 11L11.375 7.20844e-08L13 3.14286Z" fill="#999595" />
      </svg></div>
    <p class="number number_active"><b>1</b></p>
    <p class="number">2</p>
    <p class="number">3</p>
    <p class="number">4</p>
    <div class="arrow_right"><svg width="13" height="22" viewBox="0 0 13 22" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M-1.35371e-07 3.14286L8.125 11L-8.12227e-07 18.8571L1.625 22L13 11L1.625 7.20844e-08L-1.35371e-07 3.14286Z" fill="#999595" />
      </svg></div>
</div>

<style>
    .arrow_left {
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .arrow_right {
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .pagination {
        display: grid;
        grid-template-columns: 50px 50px 50px 50px 50px 50px ;
        width: 300px;
        height: 50px;
        border-radius: 30px;
        border: 1px solid gray;
        text-align: center;
   
    }
    .number {
        color: #999595;
        font-size: 24px;
        border: 1px solid gray;
        border-top: none;
        border-bottom: none;
        display: flex;
        margin: 0;
        align-items: center;
        justify-content: center;
    }
    .number_active {
        background-color: #b4bbf8;
        color: black; 
   }
</style>