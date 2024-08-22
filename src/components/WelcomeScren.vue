<template>
    <main>
    <div class="welcome-container">
      <div>
            <h1>
                Welcome to opportunity 
            </h1>
            <h2>
                {{  currentDate }}
            </h2>
    
     
        <div class="container">
            <div>
                <p class="p1">14.00 Uhr</p>
                <p class="p2"> Basisbeschäftigung Besuch</p>
                <p class="p3">Interessierte für den zweiten kurs werden uns besuchen</p>
            </div>
        </div>

        <div class="container">
            <div>    
                <p class="p1">14.00 Uhr</p>
                <p class="p2"> Basisbeschäftigung Besuch</p>
                <p class="p3">Interessierte für den zweiten kurs werden uns besuchen</p>
            </div>
        </div>

        <div class="container">
            <p class="p1">14.00 Uhr</p>
            <p class="p2"> Basisbeschäftigung Besuch</p>
            <p class="p3">Interessierte für den zweiten kurs werden uns besuchen</p>
        </div>
    </div>
  </div>
</main>  
  </template>
  
  <script>
  export default {
    name: 'WelcomeScreen',
      data() {
        return {
          currentDate: new Date().toLocaleDateString()
        }
      },
  }
  </script>
  
  <style scoped>
   main{
    width: 1080px;
    height: 1790px;
    margin: 0 auto;
    background-color: #f5f5f5; 
  }
  
  .welcome-container {
    display: flex;
    align-items: center;
    justify-self: center;
    justify-content: flex-start;
    
    padding-top: 69px;
    padding-right: 60px;
    padding-left: 60px;
    
  }
  h1{
    font-family: 'Inter', sans-serif;
    font-weight: 900;
    font-size: 62px;
    line-height: 75.03px;
    
  }
  h2 {
  font-family: 'Inter', sans-serif;
  font-weight: 500; 
  font-size: 62px;
  line-height: 75.03px;
  margin: 0; 
  color: #9AA7B1;
  padding-bottom:36px ;
}

.container{
    
    background-color: #0F05A0;
    width: 960px;
    height: 182px;
    padding-top: 34.5px;
    padding-left: 40px;
    margin-bottom: 40px;
    
    
   

}
p{
   font-family: 'Inter', sans-serif;
    font-size: 28px;
    line-height: 36px; 
}

.p1{
    color: #EB5E00;
}

.p2{
    color: #FFBFAB;
    font-weight: bold;
}
.p3{
    color: #FFBFAB;
}
 
 
  </style>