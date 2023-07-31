<template>
  
  <div class="menu">
   <a>오늘 뭐먹지? 헤헤 제발 연결되라</a>
    
  </div>

 
  
 
  
  

  <div class="bottom_menu">
  <a>image</a>
  <a>image2</a>
  <a>image3</a>
  
  </div>

</template>

<script>


export default {
  name: 'App',
  data(){
    return{
      메뉴: ['home', 'shop', 'about'],
      price1 : 60,
      price2 : 70,
      products :['역삼동원룸' ,'천호동원룸','마포구원룸'],
    }
  },
  components: {
    
  }
}
</script>

<style>
#app {
  background: rgb(255, 234, 221);
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  font-size: 20px;
  color: black;
  position: fixed;
  bottom: 0;
  left:0;
  right: 0;
  top: 0;
}

.menu {
  background: rgb(255, 137, 137);
  padding: 30px;
  border-radius: 5px;
  text-align: center;
}
.menu a {
  color: white;
  padding: 10px;
  
}

.bottom_menu {
  background:rgb(255, 137, 137);
  padding: 30px;
  border-radius: 5px;
  position: fixed;
  bottom: 0;
  left:0;
  right: 0;
}
.bottom_menu a {
  color: white;
  padding: 100px;
}
body {
  margin :0px;
}


</style>
