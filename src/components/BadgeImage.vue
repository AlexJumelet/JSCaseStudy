<template>
  <div class="BadgeImage d-flex justify-center" >
    <slot />
  </div>
</template>


<style>
.BadgeImage {
  background-color: transparent !important;
  display: flex;
  position: relative;
  height: 90px;
  top: -45px;
  margin-bottom: -15px;
}
.BadgeImage__img {
position: absolute;
  left: 50%;
  transform: translate(-50%);
height: 77px;
  width: 77px;
  z-index: 3;
 background-size: cover;
}
.BadgeImage.locked .BadgeImage__img {
  background-image: url('PNG/Badge_locked.png') ;
}
.BadgeImage.bronze .BadgeImage__img {
    background-image: url('PNG/Badge_bronze.png');
}
.BadgeImage.silver .BadgeImage__img {
   background-image: url('PNG/Badge_silver.png');
}
.BadgeImage.gold .BadgeImage__img {
  background-image: url("PNG/Badge_gold.png") ;
}
.BadgeImage.plat .BadgeImage__img {
  background-image: url("PNG/Badge_platinum.png") ;
}
.BadgeImage.bblue .BadgeImage__img {
  background-image: url("PNG/Badge_blue.png") ;
}
.BadgeImage.bred .BadgeImage__img {
  background-image: url("PNG/Badge_red.png") ;
}
.BadgeImage.bgreen .BadgeImage__img {
  background-image: url("PNG/Badge_green_eerste-keer-inloggen.png") ;
}
.BadgeImage.bpink .BadgeImage__img {
  background-image: url("PNG/Badge_pink_opleid.budget-inzetten.png") ;
}
.BadgeImage.bpurple .BadgeImage__img {
  background-image: url("PNG/Badge_purple_themas-afmaken.png") ;
}
</style>