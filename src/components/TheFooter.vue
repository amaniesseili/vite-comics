<script>
export default{
  
}

</script>

<template>

<footer>
  <div class="container">
    <div class="d-flex">
      <div class=" me-5">
        <h5><b> DC COMICS</b></h5>
        <ul class="list-unstyled">
          <li><a href="#">Characters</a></li>
          <li><a href="#">Comics</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">Tv</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">News</a></li>
        </ul>
        <h5><b> SHOP</b></h5>
        <ul class="list-unstyled">
          <li><a href="#">Shop DC</a></li>
          <li><a href="#">Shop DC Collectibles</a></li>
        </ul>
      </div>

      <div class=" me-5">
        <h5><b> DC </b></h5>
        <ul class="list-unstyled">
          <li><a href="#">terms ofUse</a></li>
          <li><a href="#">Privacy policy (new)</a></li>
          <li><a href="#">Ad Choices</a></li>
          <li><a href="#">Dvertising</a></li>
          <li><a href="#">Jobs</a></li>
          <li><a href="#">Subscriptions</a></li>
          <li><a href="#">Talent Workshopes</a></li>
          <li><a href="#">CPSC Certificates</a></li>
          <li><a href="#">Rating</a></li>
          <li><a href="#">Shop Help</a></li>
          <li><a href="#">Contact us</a></li>
        </ul>
      </div>

      <div>
        <h5><b>SITES </b></h5>
        <ul class="list-unstyled">
          <li><a href="#">DC</a></li>
          <li><a href="#">MAD Magazine</a></li>
          <li><a href="#">DC Kids</a></li>
          <li><a href="#">DC Universe</a></li>
          <li><a href="#">DC Power Visa</a></li>
        </ul>
      </div>

      <div>
        <img class="transparent-image" src="../assets/img/dc-logo-bg.png" alt="">
      </div>
    </div>
  </div>

  <!-- seconda parte del footer - sign up bar  -->
  <div class="sign-up-bar">
    
      

      <nav class="navbar navbar-expand-lg navbar-light">
        <div class="container">
            <button type="button" class="btn btn-outline-primary">Primary</button>

            <ul class="navbar-nav ">
              <li class="nav-item me-4">
                <h3 class="follow-us ">FOLLOW US</h3>
              </li>
              <li class="nav-item me-4">
                <img src="../assets/img/footer-facebook.png" alt="facebook logo">
              </li>
              <li class="nav-item me-4">
                <img src="../assets/img/footer-twitter.png" alt="twitter logo">
              </li>
              <li class="nav-item me-4">
                <img src="../assets/img/footer-youtube.png" alt="youtube logo">
              </li>
              <li class="nav-item me-4">
                <img src="../assets/img/footer-pinterest.png" alt="pinterest logo">
              </li>
              <li class="nav-item">
                <img src="../assets/img/footer-periscope.png" alt="periscope">
              </li>
            </ul>
          
        </div>
      </nav>
  </div>

</footer>


</template>




<style scoped >

footer{
  padding-top: 2rem;
  background-image: url(../assets/img/footer-bg.jpg);
}

a{
  text-decoration: none;
  color:rgb(150, 147, 147);
  font-size: smaller;
}
h5{
  color: white;
}
.transparent-image{
  margin-top: -7rem;
  margin-left: 300px;
}
.sign-up-bar{
  align-items: center;
  height: 150px;
  background-color:#303030;
}

.follow-us{
  color:#0282F9;
  font-size: 20px;
  font-weight: bold;
}
</style>