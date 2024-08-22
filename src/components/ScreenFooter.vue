<template>
  <div class="FooterContainer">
      <div class="ImgFooter">
        <img src="@/assets/img/STZH_SEB_Logo.png" alt="STZH SEB Logo" class="footer-logo" />
        <img src="@/assets/img/Opportunity.png" alt="STZH SEB Logo" class="footer-logo" />
       <img src="@/assets/img/SAG_Logo_De.png" alt="STZH SEB Logo" class="footer-logo" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style scoped>
.FooterContainer {
  
  
  background-color: ffff; 
  width: 1080px;
  height: 130px;
}

.ImgFooter {
  display: flex;
  text-align: center;
  justify-content: space-between;
  padding-left: 40px; 
  padding-right: 40px ;
  padding-top: 38px;
}

.footer-logo {
  width: 100%; 
  height: auto;
  width: 230px;
  height: 44px;
}

</style>