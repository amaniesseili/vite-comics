<script>
export default{

}

</script>

<template>

  <header>

    <nav class="navbar navbar-expand-lg navbar-light">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img class="navbar-img" src="../assets/img/favicon.ico" alt="Logo">
        </a>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link  me-3 " href="#">CHARACTERS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link me-3 active" href="#">COMICS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link me-3" href="#">MOVIES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link me-3" href="#">TV</a>
            </li>
            <li class="nav-item">
              <a class="nav-link me-3" href="#">GAMES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link me-3" href="#">COLLECTIBLES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link me-3" href="#">VIDEOS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link me-3" href="#">FANS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link me-3" href="#">NEWS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">SHOPE</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

  </header>

</template>

<style scoped >
  .navbar {
    background-color:white;
    display: flex;
    height: 100px;
  }
  .navbar-brand {
    margin-right: auto;
    flex-grow: 1;
  }
  .navbar-img{
    width: 70px;
  }
  .navbar-nav .nav-link {
    color: black;
    transition: color 0.3s;
  }
  .navbar-nav .nav-link:hover {
    color: blue;
  }
  .navbar-nav .nav-link.active {
    color: blue;
    border-bottom: 4px solid blue;
    padding-bottom: 2rem;
  }
</style>