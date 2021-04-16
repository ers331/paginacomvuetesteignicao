<template>
    <div class="container-main">
        <div class="menu-lateral">
            <div class="vt1">
            <div class="logo logo2">
                <img src="@/assets/img/logo.svg" alt="">
                <p>Ignição Digital</p></div> </div>
                <div class="dsb">
                    <div>
                   <select>
                <option>Área do cliente</option>
                <option>Fórmula Lançamento</option>
                <option>Érico Rocha</option>
                </select></div>

                <span id="area" class="chevron-down">
                    <svg width="12" height="7" viewBox="0 0 12 7" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M1 1L6 6L11 1" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                    </span>
</div><svg class="home" width="16" height="18" viewBox="0 0 16 18" fill="none" xmlns="http://www.w3.org/2000/svg">
    <path fill-rule="evenodd" clip-rule="evenodd" d="M1 6.44444L8 1L15 6.44444V15C15 15.8591 14.3036 16.5556 13.4444 16.5556H2.55556C1.69645 16.5556 1 15.8591 1 15V6.44444Z" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
    <path d="M5.66663 16.5556V8.77783H10.3333V16.5556" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
    </svg>
                </div>
                <div class="Apps">
                    <div class="apps2">
                        <p>APPS</p>
                    
                    <span><svg width="18" height="16" viewBox="0 0 18 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M2.6 1.22803H15.4C16.28 1.22803 17 1.95176 17 2.83632V12.4861C17 13.3706 16.28 14.0943 15.4 14.0943H2.6C1.72 14.0943 1 13.3706 1 12.4861V2.83632C1 1.95176 1.72 1.22803 2.6 1.22803Z" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M17 2.83643L9 7.3039L1 2.83643" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg></span><span> Email </span>
                        <svg width="18" height="19" viewBox="0 0 18 19" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M17 12.1467C17 13.1337 16.2041 13.9337 15.2222 13.9337H4.55556L1 17.5077V3.21179C1 2.22487 1.79594 1.4248 2.77778 1.4248H15.2222C16.2041 1.4248 17 2.22487 17 3.21179V12.1467Z" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg><span>Conversar</span>
                            <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M6.05261 8.40892L8.57893 10.9483L17 2.48364" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                <path d="M16.1579 9.25542V15.1807C16.1579 16.1157 15.4038 16.8736 14.4737 16.8736H2.68421C1.75405 16.8736 1 16.1157 1 15.1807V3.33014C1 2.39516 1.75405 1.63721 2.68421 1.63721H11.9474" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                </svg><span>Todo</span><br>
                                <svg width="18" height="21" viewBox="0 0 18 21" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <rect x="1" y="3.85474" width="16" height="16.0829" rx="2" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                    <path d="M12.5 1.84448V5.86521" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                    <path d="M5.5 1.84448V5.86521" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                    <path d="M1 9.38345H17" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                    </svg><span>Calendário</span>
                </div>
                    </div></div>
</template>


<style>
.container {
    width: 280px;
    height: 1960px;
    position: absolute;
    left: 0%;
    right: 85.42%;
    bottom: 0%;
}

.menu-lateral {
    background: #ffffff;
    box-shadow: 0px 2px 18px rgba(0, 0, 0, 0.178509);
    width: 280px;
    height: 2220px;
    
}

.logo {
    width: 158px;
    height: 51.1px;
    left: 44px;
    top: 29px;
    position: absolute;
}

.logo p {
    position: absolute;
    width: 100.85px;
    height: 28.84px;
    left: 60px;
    top: 15px;
    font-family:"PT Sans";
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 21px;
    color: #FF7B1B;

}

.logo2 {
    width: 51.1px;
    height: 51.1px;
    top: 29px;
    left: 44px;
    background: #FF7B1B;
    border-radius: 50%;

}

.logo img {
    padding-top: 10px;
    padding-left: 15px;
}

.dsb {
    width: 236px;
    height: 36px;
    top: 106px;
    position: absolute;
    border-radius: 6px;
    background: #ECECEC;
    left:1%


}

.dsb select {
    position: absolute;
    left: 17%;
    top: 1px;
    background: #ECECEC;
    font-family: "Montserrat";
    width: 80%;
    font-weight: 400;
    font-style: normal;
    line-height: 40px;
    color: #2c2c2c;
    border-radius: 4px;
    height: 25px;
    cursor: pointer;

}

.chevron-down {
    position: absolute;
    top: -5%;
    right: 5%;
    height: 100%;
    width: 1.5rem;
    display: flex;
    -webkit-box-align: center;
    align-items: center;
    -webkit-box-pack: center;
    justify-content: center;
    pointer-events: none;
    cursor: pointer;
    
}
.home {
    margin-top: 114px;
    margin-left: 35px;
    position: relative;
   }
   

.Apps {
    width: 112px;
    height: 194.91px;
    top: 220,09px;
    left: 37px;
    position: absolute;
    bottom: 78.83%;
    display: flex;
    flex-direction: column;


}

.apps2 p {
    font-family: "Montserrat";
    font-size: 14px;
    font-style: normal;
    line-height: 36px;
    color: #999999;
}

.apps2 svg {
    margin-right: 0.80rem;
    cursor: pointer;
    margin-top: -0.3rem;
}

.apps2 span {
    font-size: 15px;
    font-family: "Montserrat";
    font-weight: 400;
    line-height: 40px;
    cursor:pointer ;
}


</style>

