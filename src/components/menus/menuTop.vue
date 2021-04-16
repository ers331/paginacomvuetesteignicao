<template>
   <div class="navebar">
                       <div class="navtop">
                           <div class="user">
                               <img src="@/assets/img/Oval.svg" alt="ignição digital">
                           </div>
                           <div class="cliente">
                               <p>Maria Elza</p>
                           </div>
                           <div class="vip">Cliente VIP</div>
                           <div class="lupa"><svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd" d="M9 17C13.4183 17 17 13.4183 17 9C17 4.58172 13.4183 1 9 1C4.58172 1 1 4.58172 1 9C1 13.4183 4.58172 17 9 17Z" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M19 18.9999L14.65 14.6499" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                            </svg>
                            </div>
                            <div class="sino"><svg width="20" height="22" viewBox="0 0 20 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M16 7C16 3.68629 13.3137 1 10 1C6.68629 1 4 3.68629 4 7C4 14 1 16 1 16H19C19 16 16 14 16 7" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                <path d="M11.73 19.9998C11.3722 20.6166 10.7131 20.9963 10 20.9963C9.28693 20.9963 8.6278 20.6166 8.27 19.9998" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                </svg>
                                </div>
                                <div class="star"><svg width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path fill-rule="evenodd" clip-rule="evenodd" d="M11 1L14.09 7.26L21 8.27L16 13.14L17.18 20.02L11 16.77L4.82 20.02L6 13.14L1 8.27L7.91 7.26L11 1V1Z" stroke="#BBBBBB" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                    </svg>
                                    </div>
                                    <div class="calendar"><svg width="20" height="22" viewBox="0 0 20 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <rect x="1" y="3" width="18" height="18" rx="2" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                        <path d="M14 1V5" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                        <path d="M6 1V5" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                        <path d="M1 9H19" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                        </svg>
                                        </div>
                                        <div class="email"><svg width="22" height="18" viewBox="0 0 22 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path fill-rule="evenodd" clip-rule="evenodd" d="M3 1H19C20.1 1 21 1.9 21 3V15C21 16.1 20.1 17 19 17H3C1.9 17 1 16.1 1 15V3C1 1.9 1.9 1 3 1Z" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M21 3L11 10L1 3" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                            </svg>
                                            </div>
                                            <div class="msg"><svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                <path fill-rule="evenodd" clip-rule="evenodd" d="M19 13C19 14.1046 18.1046 15 17 15H5L1 19V3C1 1.89543 1.89543 1 3 1H17C18.1046 1 19 1.89543 19 3V13Z" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                                </svg>
                                                </div>
                                                <div class="check2"><svg width="21" height="20" viewBox="0 0 21 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                                    <path d="M7 9L10 12L20 2" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                                    <path d="M19 10V17C19 18.1046 18.1046 19 17 19H3C1.89543 19 1 18.1046 1 17V3C1 1.89543 1.89543 1 3 1H14" stroke="#606060" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                                                    </svg>
                                                    </div>
                       </div>
                </div>
</template>

<style>
.navebar {
    width: 1500px;
    height: 62px;
    position: absolute;
    left: 15.35%;
    right: 2%;
    top: 1.53%;
    bottom: 95.31%;
    display: flex;
}

.navtop {
    background: #FFFFFF;
    box-shadow: 0px 2px 8px rgba(0, 0, 0, 0.135216);
    border-radius: 8px;
    width: 1500px;
    height: 62px;
    top: 30px;

}

.user {
    position: absolute;
    margin-left: 96.40%;
    top: 8%;
    display: flex;
   
}

.cliente {
    font-family: "Montserrat";
    font-weight: 500;
    font-style: normal;
    font-size: 14px;
    line-height: 17px;
    position: absolute;
    margin-left: 91.80%;
    top: 20%;
    display: flex;
    color: #2c2c2c;
}

.vip {
    font-family: "Montserrat";
    font-weight: 300;
    font-size: 11px;
    line-height: 13px;
    position: absolute;
    height: 13px;
    margin-left: 92.50%;
    top: 50%;
    color: #2c2c2c;
}

.lupa {
    position: absolute;
    margin-left: 89.67%;
    top:20%;
    height: 4.35px;
    width: 4.35px;
    bottom: 96.43%;
    cursor: pointer;
}
.sino {
    position: absolute;
    margin-left: 87%;
    top: 23%;
    cursor: pointer;
}

.star {
    position: absolute;
    margin-left: 19%;
    right: 87.50%;
    top: 33%;
    cursor: pointer;
}

.calendar {
    position: absolute;
    margin-left: 23.91%;
    right: 90.20%;
    top: 33%;
    bottom: 96.90%;
    cursor: pointer;
}

.email {
    position: absolute;
    margin-left: 21.72%;
    right: 92.60%;
    top: 33%;
    bottom: 96.84%;
    cursor: pointer;
}
.msg {
    position: absolute;
    margin-left: 23.50%;
    right: 95%;
    top: 33%;
    bottom: 96.43%;
    cursor: pointer;
}

.check2 {
    position: absolute;
    margin-left: 29.80%;
    right: 97%;
    top: 33%;
    bottom: 96.43%;
    cursor: pointer;
}
</style>
<style lang="scss" scoped>
.navbartop {
    @media screen and (max-width: 800px) {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }
}
</style>

