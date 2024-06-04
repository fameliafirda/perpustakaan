<template>
  <div>
    <header class="header">
      <img loading="lazy" ref="mainImage" src="https://cdn.builder.io/api/v1/image/assets/TEMP/c1e94c9070834fac9aa9c49339d477ce78f4d74bcbabe724671b81d7f61f4caf?apiKey=6b09d60ae8314146842f414a67d69a04&" class="main-image" alt="" />
      <nav class="nav-bar">
        <div class="nav-logo">
          <img
            loading="lazy"
            src="https://cdn.builder.io/api/v1/image/assets/TEMP/5eae6aea8463a95f57a8a2cfd8eef5597abbaa9068af0108349cd63589c83050?apiKey=6b09d60ae8314146842f414a67d69a04&"
            class="logo-image"
            alt="SDN Berat Wetan 1 Library Logo"
          />
          <span class="library-name"><b>Perpustakaan SDN Berat Wetan 1</b></span>
        </div>
        <ul class="nav-links">
          <li class="nav-item"><b>Beranda</b></li>
          <li class="nav-item"><b>Informasi</b></li>
          <li class="nav-item"><b>Koleksi</b></li>
          <li class="nav-item"><b>Pustakawan</b></li>
          <li class="nav-item nav-login"><b>Login</b></li>
        </ul>
      </nav>
    </header>
    <main class="main-content">
      <section class="welcome-section">
        <h1 class="welcome-title">
          <b>Selamat Datang di Perpustakaan<br />SDN Berat Wetan 1</b>
        </h1>
        <p class="welcome-subtitle">
          <b>Membangun Generasi Cerdas dan Berbudaya Literasi</b>
        </p>
        <button class="start-button"><b>Mulai</b></button>
      </section>

      <section class="about-section">
        <h2 class="about-title">Tentang Kami :</h2>
        <p class="about-description">
          Perpustakaan SDN Berat Wetan adalah pusat sumber belajar yang
          menyediakan beragam koleksi buku dan bahan bacaan untuk mendukung
          proses belajar mengajar. Kami berkomitmen untuk meningkatkan kualitas
          pendidikan melalui layanan perpustakaan yang ramah, inovatif, dan
          berkelanjutan.
        </p>
      </section>
    </main>
  </div>
</template>

<script>
export default {
  mounted() {
    this.fitImageToScreen();
    window.addEventListener('resize', this.fitImageToScreen);
  },
  beforeDestroy() {
    window.removeEventListener('resize', this.fitImageToScreen);
  },
  methods: {
    fitImageToScreen() {
      const image = this.$refs.mainImage;
      const { innerWidth: width, innerHeight: height } = window;
      image.style.width = `${width}px`;
      image.style.height = `${height}px`;
    },
  },
};
</script>

<style scoped>
.header {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px 60px;
  background-color:;
  overflow: hidden;
  z-index: 10;
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
  padding: -10px;
}
@media (max-width: 991px) {
  .header {
    padding: 10px 20px;
  }
}
.main-image {
  object-fit: cover;
  object-position: center;
  position: absolute;
  top: 0;
  left: 0;
  z-index: -1;
}
.nav-bar {
  display: flex;
  flex-direction: row;
  align-items: center;
  width: 100%;
  max-width: 1116px;
  margin-bottom: 20px;
  position: relative;
  justify-content: space-between;
}
@media (max-width: 991px) {
  .nav-bar {
    flex-direction: column;
    margin-bottom: 20px;
  }
}
.nav-logo {
  display: flex;
  flex-direction: row;
  align-items: center;
  width: auto;
  position: relative;
  margin-top: -20px;
}
@media (max-width: 991px) {
  .nav-logo {
    width: 90%;
    justify-content: center;
    margin-top: 0;
    margin-left: -70px;
  }
}
.logo-image {
  width: 80px;
  height: auto;
  object-fit: contain;
  position: relative;
  margin-top: -10px;
  margin-left: -70px;
}
.library-name {
  color: #fff;
  font: 400 26px Lalezar, sans-serif;
  margin-left: -10px;
}
@media (max-width: 991px) {
  .library-name {
    margin-left: 0;
    margin-top: 10px;
  }
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 20px;
  margin-left: auto;
  margin-right:50px;
  list-style-type: none;
  color: #fff;
  margin-top : 10px;

}
@media (max-width: 991px) {
  .nav-links {
    flex-direction: column;
    margin-top: 10px;
  }
}
.nav-item {
  font-family: Kreon, sans-serif;
  cursor: pointer;
}
.nav-login {
  background-color: #ddebff;
  padding: 10px 20px;
  color: #d4167d;
  text-align: center;
  border-radius: 10px;
  font: 400 18px Jomhuria, sans-serif;
  margin-top: 10px;
}
@media (max-width: 991px) {
  .nav-login {
    padding: 5px 15px;
  }
}

.main-content {
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

.welcome-section {
  text-align: center;
  margin-top: 5px;
}
@media (max-width: 991px) {
  .welcome-section {
  }
}
.welcome-title {
  color: #fff;
  font: 400 48px Times New Roman;
  margin-top: -10px;
}
@media (max-width: 991px) {
  .welcome-title {
    font-size: 32px;
  }
}
.welcome-subtitle {
  color: #fff;
  text-shadow: 4px 4px 4px #000;
  margin-top: 0px;
  font: 400 26px Times New Roman;
}

.start-button {
  background-color: #bbd6ff;
  color: #d4167d;
  padding: 15px 30px;
  margin-top: 50px;
  border: 8px solid transparent;
  border-radius: 35px;
  font: 400 24px Times New Roman;
}
@media (max-width: 991px) {
  .start-button {
    margin-top: -80px;
    padding: -30px 20px;
  }
}

.about-section {
  background-color: #ddebff;
  color: #000;
  text-align: center;
  padding: 40px 60px;
  margin-top: 90px;
  width: 100%;
  max-width: 1200px;
  margin: 0;
  padding-left: -70px;
  object-fit: cover;
  object-position: center;
  position: absolute;
  top: 550px;
  left: 0;
  z-index: -1;
  
}
@media (max-width: 991px) {
  .about-section {
    padding: 0px 0px;
    margin-top: 10px;
  }
}
.about-title {
  font-weight: 700;
  font-size: 24px;
  margin-bottom: 20px;
}
.about-description {
  font: 400 20px Lexend Deca, sans-serif;
}
</style>
