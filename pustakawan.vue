<template> 
  <div class="container"> 
    <header class="header"> 
      <div class="logo-container"> 
        <figure class="logo-wrapper"> 
          <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/5eae6aea8463a95f57a8a2cfd8eef5597abbaa9068af0108349cd63589c83050?apiKey=6b09d60ae8314146842f414a67d69a04&" class="logo-image" alt="Perpustakaan SDN Berat Wetan 1 Logo"/> 
        </figure> 
        <div class="library-name"><b>Perpustakaan SDN Berat Wetan 1</b></div> 
      </div> 
      <nav class="main-nav"> 
        <ul class="nav-list"> 
          <li class="nav-item"><b>Beranda</b></li>
          <li class="nav-item"><b>Informasi</b></li>
          <li class="nav-item"><b>Koleksi</b></li>
          <li class="nav-item"><b>Pustakawan</b></li>
          <li class="nav-item login-btn"><b>Login</b></li>
        </ul> 
      </nav> 
    </header> 
    <section class="info-section"> 
      <h1 class="section-title"><b>Pustakawan</b></h1> 
      <div class="info-container"> 
        <article class="info-article"> 
          <p class="article-text"><strong>Nama:</strong><br/>Lilik Nur Hayati, S.Pd</p> 
          <p class="article-text"><strong>Jabatan:</strong><br/>Pustakawan</p> 
          <p class="article-text"><strong>E-Mail:</strong><br/>lilik.nur246@guru.sd.belajar.id</p> 
          <div class="image-grid"> 
            </div> 
        </article> 
        <aside class="service-hours"> 
          <figure class="service-image-wrapper"> 
            <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/d1525b52326e8a5ebb1ba1b4991a65d9f1421f4a5bc65cb34cb1428c2d295561?apiKey=6b09d60ae8314146842f414a67d69a04&" class="profile-image" alt="Profile picture of Lilik Nur Hayati, S.Pd" />
          </figure>  
        </aside> 
      </div> 
    </section> 
  </div> 
</template> 
<style scoped>
  html, body {
    height: 100%;
    margin: 0;
    background-color: #fff;
  }

  .container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-height: 100vh;
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    background-color: #fff;
  }

  .header {
    background-color: #e3589b;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 10px 20px;
    width: 100%;
    box-sizing: border-box;
  }

  .logo-container {
    display: flex;
    align-items: center;
    gap: 20px;
  }

  .logo-wrapper {
    width: 84px;
    height: auto;
  }

  .logo-image {
    width: 100%;
    height: auto;
  }

  .library-name {
    color: #fff;
    font: 400 26px Lalezar, sans-serif;
  }

  .main-nav {
    display: flex;
    flex-grow: 1;
    justify-content: flex-end;
  }

  .nav-list {
    display: flex;
    align-items: center;
    gap: 20px;
    list-style-type: none;
    color: #fff;
  }

  .nav-item {
    font-family: Kreon, sans-serif;
    cursor: pointer;
  }

  .login-btn {
    background-color: #ddebff;
    padding: 10px 20px;
    color: #d4167d;
    text-align: center;
    border-radius: 30px;
    font: 400 18px Jomhuria, sans-serif;
  }

  .info-section {
    color: #d4167d;
    text-align: center;
    margin-top: 29px;
    font: 400 40px Angkor, sans-serif;
  }

  .section-title {
    margin: 64px 15px 0;
    font-size: 60px;
    margin-top: 5px;
  }

  .info-container {
    display: flex;
    gap: 20px;
    margin: 64px 15px 0;
  }

  .info-article {
    flex-grow: 1;
    width: 74%;
  }

  .article-heading {
    color: rgb(0, 0, 0);
    font: 400 32px Tiro Bangla, sans-serif;
  }

  .article-text {
    font-family: Nunito, -apple-system, Roboto, Helvetica, sans-serif;
    font-size: 28px;
  }

  .image-grid {
    margin-top: 18px;
    display: flex;
    gap: 20px;
  }

  .image-item {
    width: 50%;
  }

  .info-image {
    width: 100%;
    object-fit: cover;
    object-position: center;
  }

  .service-hours {
    display: flex;
    flex-direction: column;
    width: 26%;
    margin-left: -500px;
  }

  .service-image-wrapper {
    aspect-ratio: 1.1;
    width: 10%;
    margin-left: -900px;
    
  }

  .service-image {
    width: 10px;
  }

  .service-text {
    font-family: Nunito, sans-serif;
    font-size: 28px;
  }

  .service-title {
    font-weight: 700;
    margin-top: 20px;
  }

  @media (max-width: 991px) {
    .header {
      flex-direction: column;
      align-items: flex-start;
    }

    .logo-container {
      width: 100%;
    }

    .main-nav {
      width: 100%;
      margin-top: 10px;
    }

    .nav-list {
      justify-content: space-between;
      width: 100%;
      flex-wrap: wrap;
    }

    .info-container {
      flex-direction: column;
    }

    .info-article, .service-hours {
      width: 100%;
    }
  }
</style>
