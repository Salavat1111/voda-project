<template>
  <div id="app">
    <div class="header__block">
    <div class="block__text">
        <div class="text__conteiner">
            <img id="btl" src="./icons/Mask Group.png" alt="">
            <h1 id="wh">Чистая Вода</h1>
            <p>Питьевая вода, предназначенная для ежедневного потребления, 
                идеально подходит для кулеров. 
                Закажите доставку воды и мы привезем её на дом или в офис.</p>
        </div>
        <div class="block__item">
            <div class="dan__list">
                <h1 id="zpd">Заполните данные</h1>
                <div class="cul">
                    <input class="inp" type="text" placeholder="Ф.И.О"> 
                    <input class="inp" type="text" placeholder="@email.ru">
                </div>
                <div class="cul">
                    <input class="inp"  type="text" placeholder="8 800 300 25 25" > 
                    <input class="inp" type="text" placeholder="Ведите свой адрес">
                </div>
                <p class="clb"><input type="checkbox" > Я согласен на <strong v-bind:style="{ color: '#455273' }">обработку персональных данных</strong></p>
            </div>
<div class="line"></div>
            <div class="data__block">
                <div class="voda">
                    <h1>Вода</h1>
                    <img class="heg_weg" src="./icons/Group 19.png" alt="">
                    <img class="heg_weg" src="./icons/Group 17.png" alt="">
                    <img class="heg_weg" src="./icons/Group 20.png" alt="">
                    <div class="crug">
                        <img id="crug-img" src="./icons/Group 188.png" alt="">
                        <p>1</p>
                        <img id="crug-imp2" src="./icons/Group 187.png" alt="">
                    </div>
                </div>

                <div class="data__vr">
                    <h1>Дата и время доставки</h1>
                    <div class="icon__menu">
                    <p id="den__one">День</p>
                    <img id="icons22" src="./icons/22 (9).png" alt="">
                    <img id="icons22" src="./icons/22(2).png" alt="">
                    <img id="icons22" src="./icons/22 (3).png" alt="">
                    <img id="icons22" src="./icons/22 (4).png" alt="">
                    <img id="icons22" src="./icons/22 (5).png" alt="">
                    <img id="icons22" src="./icons/22 (6).png" alt="">
                    <img id="icons22" src="./icons/22 (7).png" alt="">
                    <img id="icons22" src="./icons/22 (8).png" alt="">
                    <img id="icons22" src="./icons/22 (1).png" alt="">
                    </div>
                    <div class="icons__time">
                        <p id="den__one-two">Время</p>
                        <img src="./icons/Group 197.png" alt="" id="time__tr">
                        <img src="./icons/Group 198.png" alt="" id="time__tr">
                        <img src="./icons/Group 199.png" alt="" id="time__tr">
                    </div>
                    <!-- <img class="heg_weg" src="./icons/Group 17.png" alt=""> -->
                    <!-- <img class="heg_weg" src="./icons/Group 20.png" alt=""> -->
                </div>
                    <!-- <p>ДЕНЬ</p>
                    <p>ВРЕМЯ</p> -->
   
            </div>
<div class="line"></div>
            <div class="fnish__list">
                <p>Итог</p>
                <p><label class="summa">0</label></p>
            </div>
            <hr width="90%">
            <button class="btm">Заказать воду</button>
          </div>
        </div>
      </div>
  </div>
</template>





<style lang='scss'>
// @import '~materialize-css/dist/css/materialize.min.css';
@import './assets/vvoda.css';
</style>








