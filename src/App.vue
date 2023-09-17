<script setup>

import image from '../src/assets/image-qr-code.png'


</script>

<template>
  <main>
    <div class="container">
      <div class="box">
        <div class="item">
          <img :src="image" alt="qr code">
        </div>
          <h1>Improve your font-end skills by building projects</h1>
          <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
      </div>
    </div>
  </main>

</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap');

main{
  height: 100vh;
  width: 100vw;
}

.container{
  position: absolute;
  width: 100%;
  height: 100%;
  background-color: hsl(213.6,43.86%,88.82%);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.box{
  background-color: white;
  margin: 0 auto;
  width: 320px;
  height: 500px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: start;
  border-radius: 10px;
}

.item{
  width: 90%;
  margin: 0;
  padding: 0;
}



.item img{
  position: relative;
  width: 100%;
  height: auto;
  flex: 2;
  margin: 15px 0 20px 0;
  border-radius: 10px;

}

.box h1{
  font-family: 'Outfit', sans-serif;
  font-weight: 700;
  font-size: 24px;
  text-align: center;
  margin:0 10px 10px 10px;
}


.box p{
  font-family: 'Outfit', sans-serif;
  font-weight: 400;
  font-size: 17px;
  text-align: center;
  margin:10px 10px 10px 10px;
  color: hsl(212, 45%, 89%);
}

</style>
