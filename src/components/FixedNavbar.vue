<template>
  <nav class="navbar navbar-expand-lg background-color-black-portfolio">
  <div class="container-fluid">
      <div class="d-flex flex-row ms-4">
          <!-- <img src="" alt="none"> -->
          <font-awesome-icon class="text-white fs-1" icon="circle" />
          <div class="d-flex flex-column ms-2">
          <p class="text-white m-0 p-0">Carlos Gitto</p>
          <p class="text-color-green-portfolio m-0 p-0">@CarlosGitto</p>
          </div>
      </div>
    
    <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
      <ul class="d-flex  w-75  justify-content-end navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item me-5 ">
          <a class="nav-link active fw-bolder text-decoration-none text-white" aria-current="page" href="#">Sobre mi</a>
        </li>
        <li class="nav-item me-5">
          <a class="nav-link text-decoration-none text-white" href="#">Feed</a>
        </li>
        <li class="nav-item">
          
        </li>
      </ul>
      <div class="d-flex flex-row border-white w-25 justify-content-around align-items-center">
        <button class="nav-link fw-bold text-decoration-none btn text-color-black-portfolio background-color-light-grey-portfolio border-radius-12-portfolio" href="#" tabindex="-1" aria-disabled="true">Contactame</button>

        <font-awesome-icon class="text-white fs-5 " icon="magnifying-glass" />
      </div>
   
    </div>
  </div>
</nav>
</template>

<script>
export default {
    name: 'FixedNavbar',
}
</script>

<style>

</style>