## Identitas Materi

* **Mata Pelajaran:** Informatika
* **Kelas:** 8
* **Bab:** 2
* **Tanggal:** Senin, 31 Juli 2026
* **Materi:** Berpikir Komputasional
* **Pemateri:** Ustadz S, S.Kom., Gr.
* **Status:** Belum diketahui

> [!NOTE]
> Mengapa BAB 2 didahulukan sebelum BAB 1? Menurut jawaban dari Pemateri bahwa:
>> "...Karena fasilitas komputer kita yang masih belum memadai dan BAB 1 itu kebanyakan praktik, jadi saya dahulukan BAB 2 dulu..."
---

# Berpikir Komputasional

## Fungsi Komputasi
  Dalam Informatika, **Fungsi** adalah mekanisme yang menerima masukan (input), mengolah (proses), kemudian menghasilkan keluaran (output). Serupa dengan proses komputasi. <br> Salah satu contoh sederhana:
1. Input - Nilai Siswa
2. Proses - Menghitung nilai rata-rata
3. Output - Nilai Akhir
   
<img src="../img/informatika-1-flowchart.png" alt="Contoh Flowchart" width="100%">

## Himpunan
  **Himpunan** adalah kumpulan objek yang memiliki kesamaan ciri yang jelas sehingga dapat ditentukan apakah termasuk elemen/individu dalam sebuah himpunan atau tidak.

## Data Terstruktur
  **Data Terstruktur** adalah data yang tersusun secara rapi sehingga mudah dibaca dan diolah. <br> Berikut ialah manfaatnya:
  1. Mudah dicari
  2. Mudah diolah
  3. Mudah dianalisis
  4. Mengurangi kesalahan

## Persoalan Logika dengan Himpunan
  **Himpunan Data Terstruktur** juga dapat digunakan untuk memecahkan persoalan logika dengan memanfaatkan operasi himpunan agar lebih terorganisir.
  ### Operasi Himpunan
  * Gabungan - Semua anggota dari semua himpunan
  * Irisan - Anggota yang sama
  * Selisih - Anggota yang hanya ada pada salah satu himpunan

## Representasi Bilangan
  **Representasi bilangan** adalah cara menuliskan atau menyatakan suatu angka menggunakan sistem bilangan tertentu, seperti desimal, biner, oktal, dan heksadesimal. Walaupun penulisannya berbeda, nilai bilangannya tetap sama.

<table>
  <thead>
    <tr>
      <th>Desimal (Basis 10)</th>
      <th>Biner (Basis 2)</th>
      <th>Oktal (Basis 8)</th>
      <th>Heksadesimal (Basis 16)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <!-- DESIMAL -->
       <td>Sistem bilangan yang paling sering <br>digunakan sehari-hari<br>
         <b>Ciri-ciri:</b>
         <ul>
         <li>
           Basis = 10
         </li>
         <li>
           Digit = 0 sampai 9
         </li>
         <li>
           Contoh = 25, 125, 2024
         </li>
        </ul>
        <p align="center">Contoh: 2024<sub>10</sub></p>
        <table align="center">
          <thead>
            <tr>
              <th>Ribuan</th>
              <th>Ratusan</th>
              <th>Puluhan</th>
              <th>Satuan</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>2</td>
              <td>0</td>
              <td>2</td>
              <td>4</td>
            </tr>
            <tr>
              <td>2x10<sup>3</sup></td>
              <td>0x10<sup>2</sup></td>
              <td>2x10<sup>1</sup></td>
              <td>4x10<sup>0</sup></td>
            </tr>
          </tbody>
        </table>
      </td>
      <!-- BINER -->
      <td> Sistem bilangan yang digunakan komputer karena hanya mengenal 2 keadaan (1 dan 0)<br>
        <b>Ciri-ciri:</b>
        <ul>
          <li>Basis</li>
          <li>Digit</li>
          <li>Contoh: 1010, 1100, 11110011</li>
        </ul>
        <p align="center">Contoh: 1011<sub>2</sub></p>
        <table align="center">
          <thead>
            <tr>
              <th>2<sup>3</sup></th>
              <th>2<sup>2</sup></th>
              <th>2<sup>1</sup></th>
              <th>2<sup>0</sup></th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1</td>
              <td>0</td>
              <td>1</td>
              <td>1</td>
            </tr>
            <tr>
              <td>8</td>
              <td>0</td>
              <td>2</td>
              <td>1</td>
            </tr>
          </tbody>
        </table>
      </td>
      <!-- OKTAL -->
      <td> Sistem bilangan dengan basis 8, menggunakan digit 0-7
        <b>Ciri-ciri:</b>
        <ul>
          <li>Basis = 8</li>
          <li>Digit = 0 sampai 7</li>
          <li>Contoh = 17, 125, 765</li>
        </ul>
        <p align="center">Contoh: 17<sub>8</sub></p>
        <table align="center">
          <thead>
            <th>8<sup>2</sup></th>
            <th>8<sup>1</sup></th>
            <th>8<sup>0</sup></th>
          </thead>
          <tbody>
            <tr>
              <td>1</td>
              <td>7</td>
              <td>0</td>
            </tr>
            <tr>
              <td>64</td>
              <td>8</td>
              <td>1</td>
            </tr>
          </tbody>
        </table>
      </td>
      <td>Sistem bilangan dengan basis 16, menggunakan digit 0-9 dan A-F
        <b>Ciri-ciri:</b>
        <ul>
          <li>Basis = 16</li>
          <li>Digit = 0-9 dan A-F</li>
          <li>Contoh = 1A, 2F, 3E, FF</li>
        </ul>
        <p align="center">Contoh: 2F<sub>16</sub></p>
        <table align="center">
          <thead>
            <tr>
              <th>16<sup>1</sup></th>
              <th>16<sup>6</sup></th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>2</td>
              <td>F</td>
            </tr>
            <tr>
              <td>32</td>
              <td>15</td>
            </tr>
          </tbody>
        </table>
      </td>
    </tr>
  </tbody>
</table>

  
---

### Kredibilitas Materi: [X]
### Sumber Materi:
### Kontributor:
  * **Iqbal G.I.** (Penulis, Perangkum)
