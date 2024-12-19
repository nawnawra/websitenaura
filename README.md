<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Website Naura</title>
    <link rel="stylesheet" type="text/css" href="style.css" />
  </head>
  <style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Google Sans Regular";
    text-decoration: none;
    list-style: none;
  }
  body {
    background:#E8D8C4;
    height: 100vh;
  }
  .hero {
  width: 100%;
  height: 60px;
  background:#561C24;
  display: flex;
  align-items: center;
  justify-content: center;
  }

  nav ul {
    display: flex;
  }
  nav ul li{
    margin: 0 20px;
  }
  nav ul li a {
    display: block;
    color: #C7B7A3;
    font-size: 17px;
    padding: 5px 10px;
    border-radius: 10px;
    transition: 0.5s;
    margin: 0 5px;
  }
  nav ul li a:hover{
    color: #561C24;
    background: white
  }
  .detel{
    width: 100%;
    height: 130px;
    background-color: #E8D8C4;
  }
  .detel h1{
    font-size: 33px;
    color: #15133C;
    line-height: 80px;
    margin-bottom: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .detel span{
    color: #6D2932;
    margin-right: 5px;
    margin-left: 10px;
  }
  .detel p{
    font-size: 20px;
    color: #15133C;
    line-height: 3px;
    margin-bottom: 8px;
    display: flex;
    justify-content: center;
  }
  .content span{
    color: #15133C;
    margin-left: 10px;
  }
.content ul li strong{
  color: #15133C;
}
  .content {
    padding: 20px;
    color : #6D2932;
    margin-left: 10px;
}
.table-container {
    overflow-x: auto;
}
table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
  
}
table th, table td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: left;
}
table th {
    background-color: #561C24;
    color:#C7B7A3;
}
.btn {
    display: inline-block;
    padding: 10px 20px;
    margin: 10px 0;
    color: #6D2932;
    background-color:#561C24;
    text-decoration: none;
    border-radius: 10px;
    text-align: center;
}
.btn:hover {
    background-color: #561C24;
}
table tr th:hover{
display: flexbox;
color: #6D2932;
background: #E8D8C4;
border-radius: 5px;
transition: 0.3s;
}
  </style>
  <body>
    <header>
      <div class="detel">
        <h1>𐙚 <span> Selamat Datang </span> 𐙚</h1>
        <p>Ini adalah Website tentang Naura. Salam Kenal yaa!!</p>
      </div>
    </header>
    <div class="hero">
      <nav class="navbar">
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#pendidikan">Pendidikan</a></li>
          <li><a href="#jadwal">Jadwal Kuliah</a></li>
          <li><a href="#aktivitas">Aktivitas</a></li>
        </ul>
      </nav>
    </div>
    <div class="content" id="home">
      <h2>────୨ৎ────<span>Home</span></h2>
      <p>
        Halo! Namaku Naura Ulfatin Nadya, biasa dipanggil Naura.
        Aku lahir di Banyuwangi pada tanggal 20 April 2006. Makanan favorit ku mi ayam, kalau minumnya sih aku suka matcha.
        Salam kenal,dan mari mengenal lebih dekat ᡣ𐭩.ᐟ 
      </p>
      <p><a href="https://www.instagram.com/ndynauraa/profilecard/?igsh=MTR2aDljYm1qNnA1NQ==">
        Silahkan kunjungi Instagram saya</a> </p>
    </div>
    <div class="content" id="pendidikan">
      <h2>────୨ৎ────<span>Pendidikan</span></h2>
      <ul>
        <li>
          <strong>SMP Negeri 1 Rogojampi</strong> - (2018 - 2021)
        </li>
        <li>
          <strong>SMA Negeri 1 Rogojampi</strong> - (2021-2024)
        </li>
        <li><strong>Politeknik Negeri Banyuwangi</strong> - TRPL (2024 - Sekarang)</li>
      </ul>
    </div>
    <div class="content" id="jadwal">
      <h2>────୨ৎ────<span>Jadwal Kuliah </span></h2>
      <div class="table-container">
        <table width="468" border="3" cellpadding="5" cellspacing="0" >
          <tr>
            <th width="80" >Hari</th>
            <th width="120">MatKul</th>
            <th width="96">Pukul</th>
            <th width="137" >Ruangan</th>
          </tr>
          <tr>
           <td>Senin</td>
           <td >K3</td>
           <td >09.10-10.50</td>
           <td >G7-01</td>
          </tr>
          <tr>
            <td> </td>
            <td >MTK Disrit</td>
            <td >14.10-15.50</td>
            <td >G7-04</td>
           </tr>
           <tr>
            <td >Selasa</td>
            <td >Bahasa Inggris</td>
            <td >07.30-09.10</td>
            <td >G7-02</td>
            </tr>
            <tr>
              <td ></td>
              <td >MTK Teknik</td>
              <td >09.10-10.50</td>
              <td >G7-02</td>
              </tr>
           
          <tr>
          <td >Rabu</td>
          <td >Praktikum Desain Interaksi</td>
          <td >07.30-11.40</td>
          <td>Lab Multimedia</td>
          </tr>
          <tr>
            <td >Kamis</td>
            <td >Praktikum Sistem Operasi</td>
            <td >12.30-15.50</td>
            <td>Lab Multimedia</td>
            </tr>
            <tr>
              <td >Jumat</td>
              <td >Praktikum PTI</td>
              <td >07.30-11.40</td>
              <td>A3-01</td>
              </tr>
              <tr>
                <td ></td>
                <td >Praktikum AlPro</td>
                <td >12.30-16.20</td>
                <td>Lab TUK</td>
                </tr>
                </table>
      </div>
      <div class="content" id="aktivitas">
        <h2>────୨ৎ──── <span>Aktivitas</span></h2>
        <ul>
          <li>- Sekretaris PMR</li>
          <li>- Anggota Divisi Riset RPB</li>
        </ul>
      </div>
    </div>
  </body>
</html>
