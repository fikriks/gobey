<template>
  <div id="nav">
   <div id="mobile-menu-overlay"></div>
    <nav class="navbar navbar-expand-lg fixed-top header-transparent">
      <div class="container">
        <a class="navbar-brand" href="#">
          <picture>
              <source srcset="static/assets/img/logo.webp" type="image/webp">
              <source srcset="static/assets/img/logo.png" type="image/png">
              <img src="static/assets/img/logo.png" alt="Logo Gobey" style="width:50px;object-fit: cover;">
            </picture>
        </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01"
          aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"><i class="mdi mdi-menu"> </i></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
          <div class="d-lg-none d-flex justify-content-between px-4 py-3 align-items-center">
            <picture>
              <source srcset="static/assets/img/logo.webp" type="image/webp">
              <source srcset="static/assets/img/logo.png" type="image/png">
              <img src="static/assets/img/logo.png" alt="Logo Gobey" class="logo-mobile-menu">
            </picture>
            <a href="javascript:;" class="close-menu"><i class="mdi mdi-close"></i></a>
          </div>
          <ul class="navbar-nav ml-auto align-items-center">
            <li class="nav-item active">
              <a class="nav-link" href="#home">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#tentang">Tentang</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#topik">Topik</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#statistik">Statistik</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#galeri">Galeri</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#member">Member</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#qna">Q &amp; A</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>
