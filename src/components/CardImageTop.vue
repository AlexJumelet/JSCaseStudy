<template>
    <div class="CardImageTop">
        <slot/>
    </div>
</template>


<style>
.CardImageTop {
    font: normal normal bold 16px/19px Open Sans;
    color: white;
    text-align: center;
    background: #E0F0FC 0% 0% no-repeat padding-box;
    border-radius: 0px 20px 0px 0px;
    height:77px;
}
.CardImageTop.imglocked .CardImageTop__img {
background: url("PNG/Mask Group 7.png") #B8CBDA center center;
background-size: cover;
width:100%;
height: 100%;
}
.CardImageTop.imgbronze .CardImageTop__img {
background: url("PNG/BG-badge_bronze-full@2x.png") center center;
background-size: cover;
width:100%;
height: 100%;
}
.CardImageTop.imgsilver .CardImageTop__img {
background: url("PNG/BG-badge-grey.png") center center;
background-size: cover;
width:100%;
height: 100%;
}
.CardImageTop.imggold .CardImageTop__img {
background: url("PNG/BG-badge_gold-full@2x.png") center center;
background-size: cover;
width:100%;
height: 100%;
}
.CardImageTop.plat .CardImageTop__img {
background: url("PNG/BG-badge_platinum.png") center center;
background-size: cover;
width:100%;
height: 100%;
}
.CardImageTop.imgblue .CardImageTop__img {
background: url("PNG/BG-badge_blue-full.png") center center;
background-size: cover;
width:100%;
height: 100%;
}
.CardImageTop.red .CardImageTop__img {
background: url("PNG/BG-badge-realred.png") center center;
background-size: cover;
width:100%;
height: 100%;
}
.CardImageTop.green .CardImageTop__img {
background: url("PNG/BG-badge-green.png") center center;
background-size: cover;
width:100%;
height: 100%;
}
.CardImageTop.pink .CardImageTop__img {
background: url("PNG/BG-badge-pink.png") center center;
background-size: cover;
width:100%;
height: 100%;
}
.CardImageTop.imgpurple .CardImageTop__img {
background: url("PNG/BG-badge_purple-full.png") center center;
background-size: cover;
width:100%;
height: 100%;
}
</style>