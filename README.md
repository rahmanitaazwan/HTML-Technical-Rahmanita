# HTML-Technical-Rahmanita
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatiible"  content="IE=edge">
    <meta name="viewport" content="width=device-width", initial-scale=1.0">
    <title>Pertama</title>
  </head>
  <body>
    <nav>
      <a href="#header">Website Pertamaku</a> |
      <a href="#profilku">Profilku</a> |
      <a href="#film-favoritku">Film Favoritku</a> |
      <a href="#get-in-touch">Get in Touch</a>
    </nav>
    
    <header id="header">
      <h1>Website Pertamaku</h1>
      <p>Ini adalah pertama kali saya membuat sebuah website menggunakan HTML</p>
      <a href="https://www.google.com/" target="_blank"rel="nofollow">tekan ini untuk pergi ke google</a>
    </header>

    <br>
    <br>

    <section id="profilku">
      <h1>Profilku</h1>
      <img src="images/PSX_20201217_122914.jpg" alt="fotoku" width="200px" height="200px">
      <ul>
        <li>Nama: Rahmanita</li>
        <li>
          Email:
          <a href="mailto:rahmanitaazwan@gmail.com?subject=hallo&body = Selamat pagi">
            rahmanitaazwan@gmail.com
            </a>
        </li>
        <li>Daerah: Bogor</li>
        <li>Hobi
          <ol>
            <li>Tidur</li>
            <li>Makan</li>
            <li>Nongkrong</li>
          </ol>
        </li>
      </ul>
    </section>

    <br>
    <br>

    <section id="film-favoritku">
      <h1>Film Favoritku</h1>
      <table border="1">
        <tr>
          <th>No</th>
          <th>Nama</th>
          <th>Produsen</th>
        </tr>
        <tr>
          <td>1</td>
          <td>Hospital Playlist</td>
          <td>CJ ENM</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Penthouse</td>
          <td>Studio S(SBS)</td>
        </tr>
        </table>
    </section>


    <br>
    <br>

    <section id="get-in-touch">
      <h1>Get in touch</h1>
      <form>
        <label for="nama">Nama: </label>
        <input type="text" id="nama" name="nama"><br>
        <label for="email">Email: </label>
        <input type="text" name="email" id="email"><br><br>
        <input type="submit" value="submit"><br>
      </form>
    </section>
  </body>
</html>
