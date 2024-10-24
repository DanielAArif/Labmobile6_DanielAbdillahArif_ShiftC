# Labmobile6_DanielAbdillahArif_ShiftC

# Screenshot Aplikasi

![](Screenshot(260).png)

# Cara menambahkan komponen card ke halaman Projek Ionic (Template Blank)

1. Pastikan Projek Ionic dengan template Blank sudah dibuat.
2. Masukkan kode untuk menambahkan komponen card yang diambil dari web dokumentasi Ionic ke file home.page.html yang berada di direktori src/app/home/ seperti di bawah ini:

<ion-card>
  <ion-card-header>
    <ion-card-title>Card Title</ion-card-title>
    <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
  </ion-card-header>

  <ion-card-content>
    Here's a small text description for the card content. Nothing more, nothing less.
  </ion-card-content>
</ion-card>

3.  Ubah kodenya dan tambahkan tag <div> dengan id = card untuk membungkus kode di atas, sehingga hasilnya seperti di bawah ini:

<div id='card'>
    <ion-card>
      <ion-card-header>
        <ion-card-title>DANIEL ABDILLAH ARIF</ion-card-title>
        <ion-card-subtitle>H1D022055</ion-card-subtitle>
      </ion-card-header>
    
      <ion-card-content>
        Pertemuan 6 Praktikum Pemrograman Mobile Shift C
      </ion-card-content>
    </ion-card>
  </div>

4.  Selanjutnya masukkan kode di bawah ini ke file home.page.scss yang ada di direktori src/app/home/:

#card {
  max-width: 300px;
  margin: 0 auto;
}

Kode di atas digunakan untuk mengatur max-width dan margin dari komponen dengan id = card.
