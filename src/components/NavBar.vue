<template>
    <nav class="navbar sticky-top navbar-expand-lg bg-body-tertiary rounded shadow-sm p-1">
      <div class="container-fluid">
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarsExample11" aria-controls="navbarsExample11" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
        <div class="collapse navbar-collapse d-lg-flex" id="navbarsExample11">
          <div class="d-lg-flex col-lg-3 justify-content-lg-start mt-1 ms-1">
            <img src="../assets/goteam-logo-dark.png" alt="mdo" width="120" height="35">
            <ul class="navbar-nav col-lg-8 justify-content-lg-center">
              <li class="nav-item">
                <a class="nav-link" style="color: rgb(144, 142, 157); font-size: 15px; font-weight: 400;" aria-current="page" href="#">Careers</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" style="color: rgb(144, 142, 157); font-size: 15px; font-weight: 400;" href="#">Find your Role</a>
              </li>
            </ul>
          </div>
          <ul class="navbar-nav col-lg-6 justify-content-lg-center">
            <form class="d-flex">
              <div class="input-group">
                <input class="form-control me-2 rounded-pill ps-4" style="width:480px; height: 45px;" type="search" placeholder="Type for your job title or role" aria-label="Search">
                <button class="btn btn-primary rounded-pill d-flex p-1" style="width: 20%;" type="submit">
                  &nbsp;&nbsp;<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search mt-1" viewBox="0 0 16 16">
                      <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                    </svg>
                    &nbsp;Search
                </button>
              </div>
            </form>
          </ul>
          <div class="d-lg-flex col-lg-3 justify-content-lg-end"> 
            <div class="d-flex gap-2 w-100 justify-content-end">
              <div class="text-end">
                <p class="mb-0" style="font-weight: 600;">Mark Anthony Olivares</p>
                <a href="#" class="mb-0 link-underline link-underline-opacity-0" style="color: rgb(0, 102, 255); font-weight: 300;">olivaresmarkanthony14@gmail.com</a>
              </div>
              <a href="#" class="d-block link-body-emphasis text-decoration-none dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
                <img src="../assets/profile.jpg" alt="mdo" width="40" height="40" class="rounded-circle border">
              </a>
            </div>
          <ul class="dropdown-menu text-small">
            <li><a class="dropdown-item" href="#">Profile</a></li>
            <li><a class="dropdown-item" href="#">Settings</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Sign out</a></li>
          </ul>
          </div>
        </div>
      </div>
    </nav>
</template>

<script>
export default {
  name: 'navBar',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.container-fluid {
  margin:10px 12px;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #050505;
}
button.btn {
  position: absolute;
  right: 18px;
  top: 5px;
  padding: 2px;
  z-index: 999;
  height: 34px;
  width: 70px;
}
</style>
