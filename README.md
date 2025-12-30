<html>
  <head>
    <meta charset="UTF-8" />
    <title>Untuk Kamu</title>
    <style>
      body {
        background: #faf7f2;
        font-family: Arial, sans-serif;
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
        margin: 0;
      }
      .card {
        width: 90%;
        max-width: 500px;
        background: white;
        padding: 28px;
        border-radius: 18px;
        box-shadow: 0 0 24px rgba(0,0,0,0.08);
        text-align: center;
      }
      #text {
        font-size: 15px;
        line-height: 23px;
        white-space: pre-line;
        text-align: left;
        opacity: 0;
      }
      audio {
        display: none;
      }
    </style>
  </head>

  <body>
    <audio id="bgm" autoplay loop>
      <source src="https://litter.catbox.moe/uwmrq71prfaw879b.mp3" type="audio/mpeg" />
    </audio>
<div class="card">
  <h1>Hai, Cena.</h1>

  <p id="text">
Sebelum tahun ini selesai,
aku cuma ingin berterima kasih.
Untuk hadirmu yang lembut.
Untuk kata yang menenangkan.
Untuk waktu yang kamu bagi tanpa aku minta.
Kamu jadi warna yang indah di ceritaku tahun ini.
Sederhana, tapi terasa.

Sejak pertama ketemu,
aku tidak pernah membayangkan kita sampai sejauh ini.
Ngobrol sampai lupa jam.
Cerita sampai hati lega.
Berbagi mimpi, pandangan, dan sisi diri yang biasanya kita simpan sendiri.
Pelan-pelan, aku mulai mengenal kamu.
Dan pelan-pelan juga, kamu jadi tempat yang nyaman untuk kembali.

Dari semua obrolan itu, aku belajar tentang kamu.
Tentang caramu merasa.
Tentang caramu melihat dunia.
Tentang caramu bertahan meski harinya berat.
Sampai akhirnya aku sadar.
Ada chemistry yang tumbuh.
Ada kecocokan yang muncul diam-diam.
Ada rasa yang kita simpan dalam diam.

Aku juga dengar harapanmu.
Tentang hubungan yang tenang.
Tentang hadir yang tidak menghakimi.
Yang tidak meremehkan ceritamu.
Yang bisa menasihati dengan lembut.
Yang bisa memimpin saat kamu ragu.
Yang suaranya tetap pelan, karena keras itu bikin kamu takut.

Aku dengar semuanya, Cen.
Dan aku ingin bilang.
Aku mau mengusahakan itu.
Bukan sebagai sosok yang sempurna.
Tapi sebagai seseorang yang datang dengan niat baik.
Yang memberi ruang aman.
Biar kamu bisa jadi dirimu sendiri tanpa takut salah.

Sekarang kita bukan remaja yang jalan tanpa arah.
Kita dua orang dewasa yang paham kalau arah itu penting.
Jadi malam ini aku ingin jujur.

Aku nyaman dengan kamu.
Aku suka ritme kita yang pelan dan ringan.
Aku ingin mengenal kamu lebih dalam.
Dengan tempo yang santai.
Tanpa buru-buru.
Aku cuma ingin kamu tahu arahku.
Supaya di antara kita tidak ada tanda tanya.

Kalau kamu juga merasa hangat yang sama,
mari kita jaga ruang ini pelan-pelan.
Biar waktu yang membuktikan,
dan usaha kita yang meneruskan.

Seperti kata Tulus,
“Bila kau berkenan biarkanku di sampingmu.
Berkuranglah satu jiwa yang sepi.”

Aku tidak datang membawa kepastian yang tergesa.
Aku datang dengan langkah pelan.
Dengan kesediaan untuk tinggal.
Bukan hanya saat mudah.
Tapi juga saat hari terasa berat.

Kalau kamu mengizinkan,
aku ingin berjalan di sampingmu.
Belajar memahami diam dan suaramu.
Menjaga tanpa mengekang.
Menguatkan tanpa meninggikan suara.

Dan kalau suatu hari sepi itu kembali,
aku ingin jadi tempat ia singgah sebentar.
Bukan untuk menghapusnya.
Tapi agar ia tidak lagi terasa sendirian. </p> </div>
<script>
  const text = document.getElementById("text");
  const content = text.innerText;
  text.innerText = "";
  let i = 0;

  function typeWriter() {
    if (i < content.length) {
      text.style.opacity = 1;
      text.innerText += content.charAt(i);
      i++;
      setTimeout(typeWriter, 18);
    }
  }

  window.onload = typeWriter;
</script>
  </body>
</html>
