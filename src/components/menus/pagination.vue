<template>
<section>
    <div class="menu-paginas">
                            <div class="container-footer">
                              <div class="box">
                                <ul class="number">
                                  <li>1</li>
                                  <li>2</li>
                                  <li>3</li>
                                  <li>4</li>
                                  <li>5</li>
                                  <li>6</li>
                                  <li>7</li>
                                  <li>8</li>
                                  <li>9</li>
                                  <li>10</li>
                                </ul>
                              </div>
                            </div>
                            </div>
                            <div class="arrow-bnt"><svg  class="svg1" stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><polyline points="15 18 9 12 15 6"></polyline></svg></div>
                            <div class="arrow-bnt2"><svg class="svg2" stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><polyline points="9 18 15 12 9 6"></polyline></svg></div>

                            </section>
</template>


<style>

.svg1 {
    position: absolute;
    top: 20%;
    left: 25%;
    width: 25px;
    height: 25px;
}
.svg2 {
    position: absolute;
    top: 20%;
    left: 25%;
    width: 25px;
    height: 25px;
}
.menu-paginas {
  display: flex;
  position: absolute;
  left: 45%;
  top: 96%;
}

.box{
height: auto;
display: grid;
grid-auto-flow: column;
grid-gap: 10px;
}
.number{
display: grid;
grid-auto-flow: column;
background: #EDEDED;
border-radius: 50px;
}
.number li{
display: list-item;
font-size: 1.5em;
padding: .4rem 1rem;
transition: all .2s;
cursor: pointer;
}
.box ul {
 list-style: none;
}
.number li:hover{
background: #2c2c2c;
border-radius: 50%;
color: #fff;
}
.box > a{
background: #EDEDED;
align-self: center;
padding: 1rem 1rem;
border-radius: 50%;
}

.number li {
  text-transform: none;
}

.arrow-bnt {
  position: absolute;
  top: 96.30%;
  left: 42%;
  width: 40px;
  height: 40px;
  background: #EDEDED;
  border-radius: 50%;
  padding-left: 8px;
  padding-top: 3px;
  font-size: 20px;
  cursor: pointer;
}

.arrow-bnt2 {
  width: 40px;
  height: 40px;
  position: absolute;
  top: 96.30%;
  right: 24.4%;
  background: #EDEDED;
  border-radius: 50%;
  padding-left: 9px;
  padding-top: 3px;
  font-size: 20px;
  cursor: pointer;
  
}


.arrow-bnt:hover, .arrow-bnt2:hover {
background: #2c2c2c;
border-radius: 50%;
color: #fff;
}
</style>