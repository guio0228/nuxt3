<script setup lang='ts'>

</script>

<template>
  <container>
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
      <div class="icon">icon</div>
      <div class="search-bar">
        <i class="fas fa-search"></i>
        <input type="text" placeholder="Search...">
      </div>
    </div>
  </nav>
  <main></main>
  <footer></footer>
 </container>
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
}
}
</style>