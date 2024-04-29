<script setup lang='ts'>

</script>

<template>
  <nav>
    <div class="nav-up">
      <div class="nav-up-left">
        <div>比比昂日本購物</div>
        <div>泰國購物</div>
        <div>
         綜合服務
        </div>  
      </div>
      <div class="nav-up-right">
        <div>最近看過</div>
        <div>購物車</div>
        <div>我的訂單</div>
        <div>顧客中心</div>
        <div>下載APP</div>
        <div>註冊</div>
        <div>登入</div>
      </div>
      
    </div>
    <div class="nav-down">
      <div class="center">
      <i class="fa-solid fa-house icon"></i>
      <div class="search-bar">
        <input type="text" placeholder="Search...">
        <div class="box">
          <i class="fas fa-search"></i>
        </div>
      </div>
    </div>
    </div>
  </nav>
  <main></main>
  <footer></footer>
</template>



<style lang="scss" scoped>


nav{
  .nav-up{
     display: flex;
     justify-content: space-around;
     align-items: center;
    flex-direction: row;
    background: #7c0303;
    padding: 10px;
    color: white; 
    .nav-up-left{
       display: flex;
      gap: 4px;

    }
    .nav-up-right{
       display: flex;
       gap: 4px;
     }
  }
.nav-up-left > div:hover,
.nav-up-right > div:hover {
  cursor: pointer;
  color: #000000;
}
.nav-down{
  width: 100%;
  height: 134px;
  background: #c00909;
  display: flex;
  align-items: center;
  
  .center{
    width: 1240rem;
  height: 134px;
    display: flex;
  align-items: center;
  gap: 60px;

  .icon{
     font-size: 30px;
     color: white;
     margin-left: 250px;
  }
  .search-bar{
     display: flex;
     align-items: center;
     border-radius: 5px;
     width: 540px;
     background-color: white;
     height: 45px;
     &:hover{
      cursor: text;
     }
    input{
      width: 500px;
      height: 30px;
      border: none;
      border-radius: 5px 0 0 5px;
      background: white;    
      outline: none;
    }
    .box{
      width: 30px;
      height: 30px;
      border: none;
      border-radius: 5px; 
      background: rgb(0, 0, 0);
      display: flex;
      justify-content: center;
      align-items: center;
      i{
        font-size: 20px;
        color: rgb(255, 255, 255);
        
      }
    }
  }
}
}
}

</style>