# Lab5_javascript

Membuat dokumen HTML dengan nama file lab5_javascript.html seperti berikut.

<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Mengenal JavaScript</title>
  </head>
  <body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write and console.log</h3>
    <script type="text/javascript">
      document.write("Hello World");
      console.log("Hello World");
    </script>
  </body>
</html>

![1](https://user-images.githubusercontent.com/56192368/116348959-33b3c400-a819-11eb-811e-a14bd02266e9.JPG)


JavaScript Dasar
1, Pemakaian Alert sebagai property window.
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>alert box</title>
  </head>
  <body>
    <script type="text/javascript">
      <!--
        window.alert("Ini merupakan pesan untuk anda");
      //-->
    </script>
  </body>
</html>

![2](https://user-images.githubusercontent.com/56192368/116348989-41694980-a819-11eb-93d3-ba39b664f28c.JPG)

2. Pemakaian Method dalam objek.
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>skrip javascript</title>
  </head>
  <body>
    percobaan memakai javascript:<br>
    <script type="text/javascript">
      <!--
        document.write("Selamat mencoba Javascript<br>");
        document.write("Semoga sukses!");
      //-->
    </script>
  </body>
</html>

![3](https://user-images.githubusercontent.com/56192368/116349041-5b0a9100-a819-11eb-80f3-a92f68688b74.JPG)

3. Pemakaian prompt
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Pemasukan Data</title>
  </head>
  <body>
    <script type="text/javascript">
      <!--
        var nama = prompt("Siapa nama anda?", "Masukan nama anda");
        document.write("Hai," + nama);
      //-->
    </script>
  </body>
</html>

![4](https://user-images.githubusercontent.com/56192368/116349132-88efd580-a819-11eb-8824-d93b7147508f.JPG)


![4 1](https://user-images.githubusercontent.com/56192368/116349084-6e1d6100-a819-11eb-82fd-ab68b472fb25.JPG)

4. Pembuatan fungsi dan cara pemanggilannya.
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Contoh program javascript</title>
    <script type="text/javascript">
      function pesan(){
        alert ("Memanggil javascript lewat body onload")
      }
    </script>
  </head>
  <body onload=pesan()>
  </body>
</html>

![5](https://user-images.githubusercontent.com/56192368/116349138-8e4d2000-a819-11eb-8a33-11e29de016aa.JPG)

Dasar Pemrograman di JavaScript

1. Operasi dasar aritmatika.
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Contoh program javascript</title>
    <script type="text/javascript">
      function test (val1, val2)
      {
        document.write("<br>"+"pekalian : val1*val2 "+"<br>")
        document.write(val1*val2)
        document.write("<br>"+"pembagian : val1/val2 "+"<br>")
        document.write(val1/val2)
        document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
        document.write(val1+val2)
        document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
        document.write(val1-val2)
        document.write("<br>"+"modulus : val1%val2 "+"<br>")
        document.write(val1%val2)
      }
    </script>
  </head>
  <body>
    <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
  </body>
</html>

![6](https://user-images.githubusercontent.com/56192368/116349183-a886fe00-a819-11eb-9d0d-4cceb50b72de.JPG)

![6 1](https://user-images.githubusercontent.com/56192368/116349186-aae95800-a819-11eb-8643-1fe9c784a468.JPG)


2. Seleksi kondisi (if..else)
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>contoh if-else</title>
  </head>
  <body>
    <script type="text/javascript">
      <!--
        var nilai = prompt("nilai (0-100): ", 0);
        var hasil = "";
        if (nilai >= 60)
        hasil = "Lulus";
        else
        hasil = "Tidak Lulus";
        document.write("Hasil: "+ hasil);
      //-->
    </script>
  </body>
</html>

![7](https://user-images.githubusercontent.com/56192368/116349239-c7859000-a819-11eb-9763-536d978d6bef.JPG)

![7 1](https://user-images.githubusercontent.com/56192368/116349251-c9e7ea00-a819-11eb-830f-e79077b1ea0b.JPG)


3. Penggunaan operator switch untuk seleksi kondisi.
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Contoh program javascript</title>
    <script type="text/javascript">
      function test ()
      {
        val1=window.prompt("input nilai (1-5):")
        switch (val1)
        {
          case "1":
            document.write("Bilangan satu")
            break
          case "2":
            document.write("Bilangan dua")
            break
          case "3":
            document.write("Bilangan tiga")
            break
          case "4":
            document.write("Bilangan empat")
            break
          case "5":
            document.write("Bilangan lima")
            break
          default:
            document.write("Bilangan lainnya")
        }
      }
    </script>
  </head>
  <body>
    <input type="button" name="button1" value="switch" onclick=test()>
  </body>
</html>


![8](https://user-images.githubusercontent.com/56192368/116349308-e6842200-a819-11eb-956b-f48b676fe69e.JPG)

![8 1](https://user-images.githubusercontent.com/56192368/116349314-eb48d600-a819-11eb-9f7b-a1d309cc7cc5.JPG)


Pembuatan Form
1. Form Input.
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Form input</title>
    <script type="text/javascript">
      function test()
      {
        var val1=document.kirim.T1.value
        if (val1%2==0)
          document.kirim.T2.value="Bilangan genap"
        else
          document.kirim.T2.value="Bilangan ganjil"
      }
    </script>
  </head>
  <body>
    <form method="POST" name="kirim">
      <p>BIL <input type="text" name="T1" size="20">MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
      <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
    </form>
  </body>
</html>

![9](https://user-images.githubusercontent.com/56192368/116349362-074c7780-a81a-11eb-816e-a9c774fe563d.JPG)

2. Form Button.
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>objek document</title>
  </head>
  <body>
    <script type="text/javascript">
      <!--
      function ubahWarnaLB(warna){
        document.bgColor = warna;
      }
      function ubahWarnaLD(warna){
        document.fgColor = warna;
      }
      //-->
    </script>
    <h1>tes</h1>
    <form>
      <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
      <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
      <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
      <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
    </form>
    <script type="text/javascript">
      <!--
      document.write("Dimodifikasi terakhir pada " + document.lastModified);
      //-->
    </script>
  </body>
</html>

![10](https://user-images.githubusercontent.com/56192368/116349417-2945fa00-a81a-11eb-93a5-3469c488ef7d.JPG)


![10 1](https://user-images.githubusercontent.com/56192368/116349425-2e0aae00-a81a-11eb-9eb0-da8d7b7175d7.JPG)

HTML DOM
Pilihan menggunakan checkBox dengan perhitungan otomatis.

<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Daftar Menu</title>
    <script type="text/javascript">
      function hitung(ele){
        var total = document.getElementById('total').value;
            total = (total ? parseInt(total) : 0);
        var harga = 0;

        if (ele.checked) {
            harga = ele.value;
            total += parseInt(harga);
        }else {
            harga = ele.value;
            if (total > 0)
                total -= parseInt(harga);
        }
        document.getElementById('total').value = total;
      }
    </script>
  </head>
  <body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);"/>Ayam Goreng Rp. 5.000</label><br/>
    <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);"/>Tempe Goreng Rp. 500</label><br/>
    <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);"/>Telur Dadar Rp. 2.2500</label><br/>
    <strong>Total Bayar: Rp. <input id="total" type="text"/></strong>
  </body>
</html>

![11](https://user-images.githubusercontent.com/56192368/116349463-47abf580-a81a-11eb-888a-7666dffbe43e.JPG)



Pertanyaan dan Tugas
Buat script untuk melakukan validasi pada isian form.
Jawab
Berikut adalah script untuk melakukan validasi isian form, sebagai contoh saya membuat validasi untuk form login.
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Validasi Isian Form</title>
    <script type="text/javascript">
      function validasi() {
        var nama = document.getElementById("nama").value;
        var email = document.getElementById("email").value;
        var alamat = document.getElementById("alamat").value;
        if (nama != "" && email!="" && alamat !="") {
          return true;
        }else{
          alert('Anda harus mengisi data dengan lengkap !');
        }
      }
      </script>
    </head>
    <body>
      <h2>Validasi Isian Form</h2>
      <div class="login">
        <form action="#" method="POST" onSubmit="validasi()">
          <div>
            <label>Nama Lengkap:</label>
            <input type="text" name="nama" id="nama" />
          </div>
          <div>
            <label>Email:</label>
            <input type="email" name="email" id="email" />
          </div>
          <div>
            <label>Alamat:</label>
            <textarea cols="40" rows="5" name="alamat" id="alamat"></textarea>
          </div>
          <div>
            <input type="submit" value="Daftar" class="tombol">
          </div>
        </form>
      </div>
    </body>
</html>

![question](https://user-images.githubusercontent.com/56192368/116349502-5b575c00-a81a-11eb-9640-a2fc2f4af2e9.JPG)


![quest11](https://user-images.githubusercontent.com/56192368/116349504-5c888900-a81a-11eb-90a7-357746b01633.JPG)

            SEKIAN DAN TERIMAKASIH
