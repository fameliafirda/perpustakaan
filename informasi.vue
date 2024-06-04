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
      <h1 class="section-title"><b>Informasi</b></h1> 
      <div class="info-container"> 
        <article class="info-article"> 
          <h2 class="article-heading"><b>Informasi & kontak</b></h2> 
          <p class="article-text"><strong>Alamat:</strong><br/>Jl. H. Abdul Fattah No. 04 Dusun Berat Wetan, Kecamatan Gedeg<br/>Kabupaten Mojokerto, Jawa Timur</p> 
          <p class="article-text"><strong>Npsn:</strong><br/>20502893</p> 
          <p class="article-text"><strong>E-Mail:</strong><br/>sdn1.beratwetan@gmail.com</p> 
          <p class="article-text"><strong>Kode pos:</strong><br/>61351</p> 
          <div class="image-grid"> 
            <figure class="image-item"><img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/63a3adef3a1bc7b1c99a3834a5e940c445fa10d3dd85df69d994f0f39c32019f?apiKey=6b09d60ae8314146842f414a67d69a04&" class="info-image" alt="Informational Image 1"/> </figure> 
            <figure class="image-item"><img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/a94e22325afa76f1411a0b3206c051fdca5c5e55acb2dfd60d2caacc273ab5b2?apiKey=6b09d60ae8314146842f414a67d69a04&" class="info-image" alt="Informational Image 2"/> </figure> 
          </div> 
        </article> 
        <aside class="service-hours"> 
          <figure class="service-image-wrapper"> 
            <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/f9e682162198b089bd5dc52f3f7e93361ca6829c486c1b61bebb4964b7d37420?apiKey=6b09d60ae8314146842f414a67d69a04&" class="service-image" alt="Service Hours Image"/> 
          </figure> 
          <div class="service-text"> 
            <h2 class="service-title">Jam Pelayanan</h2> 
            <p><strong>Senin - Kamis, Sabtu:</strong><br/>Buka: 06:00 WIB<br/>Tutup: 14:00 WIB</p> 
            <p><strong>Jum’at:</strong><br/>Buka: 06:00 WIB<br/>Tutup: 13:00</p> 
          </div> 
        </aside> 
      </div> 
    </section> 
  </div> 
</template> 
<style scoped>
  html, body {
    height: 100%;
    margin: 0;
  }

  .container {
    background-color: #fff;
    display: flex;
    flex-direction: column;
    justify-content: center;
    min-height: 100vh;
    object-fit: cover;
    object-position: center;
    position: absolute;
    top: 0;
    left: 0;
    z-index: -1;
  }

  .header {
    background-color: #e3589b;
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: -10px 20px;
    
  }

  .logo-container {
    display: flex;
    width: 100%;
    max-width: 1116px;
    gap: 20px;
  }

  .logo-wrapper {
    display: flex;
    flex-direction: column;
    width: 23%;
  }

  .logo-image {
    aspect-ratio: 0.92;
    object-fit: auto;
    object-position: center;
    width: 84px;
    height: auto;
    object-fit: contain;
    position: relative;
    margin-top: 10px;
    margin-left: -35px;
  }

  .library-name {
  color: #fff;
  font: 400 26px Lalezar, sans-serif;
  margin-left: -270px;
  margin-top: 55px;
  max-width: 991px;
}
@media (max-width: 991px) {
  .library-name {
    margin-left: 0;
    margin-top: 0px;
  }
}

  .main-nav {
    display: flex;
    flex-direction: column;
    width: 50%;
    margin-left: -30px;
  }

  .nav-list {
  display: flex;
  align-items: center;
  gap: 20px;
  margin-left: 400px;
  margin-right:50px;
  list-style-type: none;
  color: #fff;
  margin-top : -105px;

}
@media (max-width: 991px) {
  .nav-list {
    flex-direction: column;
    margin-top: 10px;
  }
}

.nav-item {
  font-family: Kreon, sans-serif;
  cursor: pointer;
  margin-top: 21px;
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
    margin-top: -10px;
  }

  .info-container {
    display: flex;
    gap: 20px;
    margin: 64px 15px 0;
  }

  .info-article {
    flex-grow: 1;
    flex-direction: column;
    width: 74%;
  }

  .article-heading {
    color: rgb(0, 0, 0);
    font: 400 32px Tiro Bangla, sans-serif;
    margin-left: 0px;
    margin-top: -20px;
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
    margin-top: 130px;
  }

  .info-image {
    width: 100%;
    object-fit: auto;
    object-position: center;
  }

  .service-hours {
    display: flex;
    flex-direction: column;
    width: 26%;
  }

  .service-image-wrapper {
    aspect-ratio: 1.1;
    object-fit: auto;
    object-position: center;
    width: 10px;
    margin-bottom: 20px;
    margin-left: 0px;
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
    margin-top: 200px;
  }

  @media (max-width: 991px) {
    .header {
      padding: 0 20px;
    }

    .logo-container,
    .logo-wrapper,
    .main-nav,
    .info-container,
    .info-article,
    .image-item,
    .service-hours {
      width: 100%;
      margin-top: 40px;
    }

    .nav-list {
      flex-direction: column;
      align-items: stretch;
      gap: 0;
      margin-top: 40px;
      white-space: initial;
    }
  }
</style>
