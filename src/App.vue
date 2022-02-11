<template>
  <div id="app">
    <h1>CARA DEPLOY HEROKU</h1>
    <div>
      Heroku adalah sebuah cloud platform yang menjalankan bahasa pemrograman tertentu, Heroku mendukung bahasa pemrograman seperti Ruby, Node.js, Python, Java, PHP, dan lain-lain.
    </div>
    <h1>MANFAAT HEROKU</h1>
    <div>
      Manfaat menggunakan Heroku adalah layanannya yaitu menjalankan script app langsung tanpa memerlukan setting yang sangat rumit, memungkinkan pengembang aplikasi lebih fokus pada kode aplikasi mereka, tanpa terlalu dipusingkan dengan arsitektur dan server.
      Akan lebih mudah jika kita coba menyederhanakan seperti ini :

      saya ingin live test aplikasi saya tapi tidak menggunakan domain dulu karena ini untuk testing karena masih dalam tahap developing ada testing online sebelum menuju production.
      Saya tidak punya vps untuk mencoba app saya
      Vps saya tidak ada service atau library yang dibutuhkan oleh app saya
      saya mau demo dengan client dan app nya harus onlinekan, saya tapi saya tidak punya server/vps maklum masih baru-baru menjadi freelance
      Perusaahan tempat saya bekerja meminta sebelum di deploy atau di install ke dalam server utama diharuskan untuk berjalan dengan lancar dalam server testing dengan kriteria server tertentu
      dan lain lain.
    </div>
    <h1>CARA DEPLOY HEROKU</h1>
    <div>
      Pertama : 
      <ul>1. Register User di Heroku</ul>
      <ul>2. Instalasi heroku tolbet / Heroku CLI</ul>
      <ul>3. Kita akan clone projek kita di git server seperti github, bitbucket atau gitlab terserah saja, atau kita buat projek baru untuk di running di heroku</ul>
      <ul>4. Menghubungkan git lokal dengan heroku</ul>
      <ul>5. Deploy dan Testing
        <ul>
          <a href="https://www.codepolitan.com/membuat-proyek-pertama-heroku-58b872c6217eb"><h1>SINI</h1></a>
        </ul>
      </ul>
      
    </div>
  
    
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
  height: 100vh;
}
</style>
