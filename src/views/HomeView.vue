<script setup lang="ts">
import Logo from "@/assets/imersao/logo/Frame 57.png"
import BannerImg from "@/assets/imersao/banner/banner-main.png"

</script>

<template>
  <main>
     <header>
       <div class="logo">
        <img :src="Logo" alt="">
       </div>
       <nav>
        <ul>
          <li>CATALOGUE</li>
          <li>FASHION</li>
          <li>FAVORITE</li>
          <li>LIFESTYLE</li>
        </ul>
        <button>
          SIGN UP
        </button>
       </nav>
     </header>
     <section class="banner">
        <div class="text">
          <h1>LET´S EXPLORE UNIQUE CLOTHES.</h1>
        </div>
         <div class="Img">
          <img :src="BannerImg" alt="">
         </div>
     </section>
  </main>
</template>
<style scoped>
main{
  width: 1290px;
  margin: 0 auto;
}

main header{
  display: flex;
  justify-content: 
  space-between;
}

main header nav{
  display: flex;
  align-items: center;
  gap: 15px;
}

main header nav ul {
  padding: 0;
  list-style: none;
  display: flex;
  gap: 60px
}

main header nav ul li{
  list-style: none;
  padding: 0;
  font-size: 20px;

}

main header nav button{
  padding: 0%;
  background-color: black;
  color: white;
  border-radius: 6px;
  cursor: pointer;
}

main .banner{
  margin: 30px 0 0 0;
  display: flex;
  justify-content: space-between;
  background-color: #F4F6F5;
  border-radius: 59px;
  padding: 70px 70px 0 70px;
}

main .banner .text h1{
  font-weight: 900;
  font-size: 80px;
  padding: 0;
  margin: 0;
}

</style>
