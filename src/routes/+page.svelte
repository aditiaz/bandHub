<script>
  // Tidak ada script tambahan
  import background from '../assets/1.svg'
</script>

<style>
.background {
    position: relative; /* Ubah dari absolute ke relative */
    width: 100vw;
    height: 100vh;
    background: url('../assets/1.svg');
    overflow: hidden;
}
  .judul {
    color: white;
    font-family: 'Arial', sans-serif; /* Ganti dengan font yang sesuai */
    font-size: 24px; /* Sesuaikan ukuran font */
    font-weight: bold; /* Sesuaikan ketebalan font */
    letter-spacing: 1.5px; /* Sesuaikan jarak antar huruf */
    text-transform: uppercase; /* Jika teks di SVG adalah huruf kapital */
    text-align: center; /* Pusatkan teks */
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%); /* Pusatkan teks di tengah */
}


</style>

<div class="background">
    <!-- <img src={background} alt="Background" /> -->
     <p class="judul">Menghubungkan Band dengan IO</p>
</div>
