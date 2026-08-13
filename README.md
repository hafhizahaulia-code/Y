<!DOCTYPE html>
<html lang="id">
  <head>
    <style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    min-height: 100vh;
    padding: 40px 20px;

    font-family: 'Inter', sans-serif;
    color: #e5e5e5;

    background: #111111;

    text-align: center;
}

h1 {
    margin-bottom: 30px;

    font-size: 32px;
    font-weight: 700;
    letter-spacing: -1px;

    color: #f5f5f5;
}

form {
    width: 100%;
    max-width: 520px;
    margin: 0 auto;

    padding: 35px;

    background: #1a1a1a;

    border: 1px solid #333;
    border-radius: 18px;

    box-shadow: 0 20px 50px rgba(0,0,0,.35);
}

label {
    display: block;

    margin-top: 20px;
    margin-bottom: 9px;

    color: #d4d4d4;

    font-size: 14px;
    font-weight: 600;
}

input[type="text"],
input[type="email"],
input[type="password"],
input[type="date"],
select,
textarea {
    width: 100%;

    padding: 13px 15px;

    font-family: 'Inter', sans-serif;
    font-size: 14px;

    color: #eeeeee;
    background: #242424;

    border: 1px solid #3a3a3a;
    border-radius: 10px;

    outline: none;

    transition: .2s ease;
}

input::placeholder,
textarea::placeholder {
    color: #777;
}

input[type="text"]:focus,
input[type="email"]:focus,
input[type="password"]:focus,
input[type="date"]:focus,
select:focus,
textarea:focus {
    background: #292929;
    border-color: #777;

    box-shadow: 0 0 0 3px rgba(255,255,255,.05);
}

input[type="date"] {
    color-scheme: dark;
}

select {
    cursor: pointer;
}

select option {
    background: #1c1c1c;
    color: #fff;
}

textarea {
    min-height: 120px;
    resize: vertical;
}

input[type="radio"],
input[type="checkbox"] {
    width: 17px;
    height: 17px;

    accent-color: #e5e5e5;

    cursor: pointer;
}

input[type="submit"],
input[type="reset"],
button {
    padding: 12px 24px;

    font-family: 'Inter', sans-serif;
    font-size: 14px;
    font-weight: 600;

    color: #111;

    background: #eeeeee;

    border: none;
    border-radius: 9px;

    cursor: pointer;

    transition: .2s ease;
}

input[type="submit"]:hover,
button:hover {
    background: #ffffff;
    transform: translateY(-2px);
}

input[type="reset"] {
    color: #ddd;

    background: #292929;

    border: 1px solid #444;
}

input[type="reset"]:hover {
    background: #333;
}

hr {
    border: none;

    height: 1px;

    margin: 25px 0;

    background: #333;
}

@media (max-width: 600px) {

    body {
        padding: 25px 15px;
    }

    h1 {
        font-size: 27px;
    }

    form {
        padding: 25px 20px;
        border-radius: 15px;
    }
}
    </style>
    <meta charset="UTF-8">
    <title>Form Biodata</title>
  </head>
  <body>
    <html en="ys8m5q"
    <p align="center"></p>
    <h1>Pendaftaran Ekstrakulikuler</h1>
      <form action="#" method="post">
        <label for="nama">Nama Lengkap</label>
    <br>
        <input type="text" id="nama" name="nama">
    <br><br>
        <label for="nis">NIS</label>
    <br>
        <input type="nis" id="nis" name="nis">
    <br><br>
        <label>Email</label>
    <br>
        <input type="email">
    <br><br>
        <label>Tanggal Lahir</label>
    <br>
        <input type="date">
    <br><br>
        <label>Jenis Kelamin</label>
    <br>
        <input type="radio" name="jk">
        Laki-Laki
        <input type="radio" name="jk">
        Perempuan
    <br><br>
        <label>Pilihan Ekstrakulikuler</label>
    <br>
        <input type="checkbox">
        English Club
        <input type="checkbox">
        Basket
        <input type="checkbox">
        Badminton
        <input type="checkbox">
        Marching Band
    <br><br>
        <label>Kelas</label>
    <br>
        <select>
          <option>X RPL 1</option>
          <option>X RPL 2</option>
          <option>X RPL 3</option> 
        </select>
    <br><br>
        <label>Alasan Mengikuti Esktrakulikuler</label>
    <br>
        <textarea rows="4" cols="40"></textarea>
    <br><br>
        <input type="submit" value="Simpan">
          <input type="reset" value="Batal">
            
         </form>
  </body>
  </html>
