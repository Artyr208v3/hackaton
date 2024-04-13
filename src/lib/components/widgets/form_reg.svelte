<div class="form">
    <input type="text" placeholder="Фамилия и имя участника" class="name">
    <input type="email" placeholder="Email" class="email">
    <input type="text" placeholder="Название работы" class="work">
    <div class="input__file-wrapper">
        <p class="text-shadow">Ваша работа</p>
    <div class="input__wrapper">
        <input name="file" type="file" id="input__file" class="input input__file" multiple>
        <label for="input__file" class="input__file-button">
           <span class="input__file-icon-wrapper"><img class="input__file-icon" src="/Скрепка.png" alt="Выбрать файл" width="30"></span>
           <span class="input__file-button-text">Выберите файл</span>
        </label>
     </div>
    </div>
</div>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
    input {
        height: 62px;
        width: 472px;
      display: block;
      height: calc(2.25rem + 2px);
      padding: 0.375rem 0.75rem;
      font-family: inherit;
      font-size: 28px;
      font-weight: 400;
      line-height: 1.5;
      color: #212529;
      background-color: #fff;
      background-clip: padding-box;
      border: 1px solid #aa85da;
      border-radius: 10px;
      transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
    }
    input::placeholder {
        color: #212529;
      opacity: 0.4;
    }
    input:focus {
        color: #212529;
      background-color: #fff;
      border-color: #bdbdbd;
      outline: 0;
    }
    
    .form {
        display: flex;
        flex-direction: column;
        gap: 45px;
        align-items: center;
    }
    .text-shadow {
        opacity: 55%;
        font-size: 20px;
        margin: 0;
        font-family: 'Roboto', sans-serif;
        position: relative;
        right: 90px;
        top: 4px;
    }

    .input__file-wrapper {
        width: 498px;
        display: flex;
        justify-content: center;
        border: 1px solid #aa85da;
        border-radius: 10px;
        height: 100px;
    }

    .input__wrapper {
  position: relative;
  text-align: center;
}
 
.input__file {
  opacity: 0;
  visibility: hidden;
  position: absolute;
}
 
.input__file-icon-wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
  display: flex;
}
 
.input__file-button-text {
    display: flex;
  line-height: 1;
  margin-top: 1px;
}
 
.input__file-button {
    position: relative;
    right: -95px;
  font-size: 20px;
  font-weight: 600;
  display: flex;
          align-items: center;
          justify-content: flex-start;
  border-radius: 3px;
  cursor: pointer;
  height: 25px;
}

@media (max-width: 480px) {
    .form {
        display: flex;
        flex-direction: column;
        gap: 45px;
        align-items:flex-start;
    }
    .text-shadow {
      opacity: 55%;
        font-size: 20px;
        margin: 0;
        font-family: 'Roboto', sans-serif;
        position: relative;
        right: 0px;
        top: 4px;    }
    input {
        width: 300px;
    }
    .input__file-wrapper {
        width: 300px;
    }
    .input__file-button {
      right: 0;
    }
  }
    
</style>