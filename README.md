<!DOCTYPE html>
<html lang="en">

<head>
  <!-- Required meta tags -->
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous" />
  <link rel="stylesheet" href="stylelayout.css" />

  <title>Layout dengan Bootstrap</title>
</head>

<body>
  <div id="container">
    <header>
      <h1>Layout Sederhana</h1>
    </header>

    <!-- Menambah Navigasi -->
    <nav>
      <a href="home.html" class="active">Home</a>
      <a href="artikel.html">Artikel</a>
      <a href="about.html">About</a>
      <a href="kontak.html">Kontak</a>
    </nav>

    <!-- Menambah panel HERO -->
    <section id="hero">
      <h1>
        <b>Hello World!</b>
      </h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum
        lorem elit, iaculis innisl volutpat, malesuada tincidunt arcu. Proin
        in leo fringilla, vestibulum mi porta, faucibus felis. Integer
        pharetra est nunc, nec pretium nunc pretium ac.
      </p>
      <a href="home.html" class="btn btn-primary" role="button">Learn more &raquo;</a>
    </section>

    <!-- Menambah Wrapper, Main, row dan box -->
    <div id="wrapper">
      <section id="main">
        <div class="row">
          <div class="box">
            <img src="https://dummyimage.com/120/db7d25/fff.png" alt="" class="image-circle" />
            <h3>satu</h3>
            <p>
              Donec sed odio dui. Etiam porta sem malesuada magna mollis
              euismod.
            </p>
            <button type="button" class="btn btn-secondary">
              View detail
            </button>
          </div>
          <div class="box">
            <img src="https://dummyimage.com/120/3e73e6/fff.png" alt="" class="image-circle" />
            <h3>dua</h3>
            <p>
              Donec sed odio dui. Etiam porta sem malesuada magna mollis
              euismod.
            </p>
            <button type="button" class="btn btn-secondary">
              View detail
            </button>
          </div>
          <div class="box">
            <img src="https://dummyimage.com/120/71e6d4/fff.png" alt="" class="image-circle" />
            <h3>tiga</h3>
            <p>
              Donec sed odio dui. Etiam porta sem malesuada magna mollis
              euismod.
            </p>
            <button type="button" class="btn btn-secondary">
              View detail
            </button>
          </div>
        </div>

        <hr class="divider" />
        <article class="entry">
          <h2>First featurette heading.</h2>
          <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" />
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
            tincidunt arcu. Proin in leo fringilla, vestibulum mi porta,
            faucibus felis. Integer pharetra est nunc, nec pretium nunc
            pretium ac.
          </p>
        </article>
        <hr class="divider" />
        <article class="entry">
          <h2>First featurette heading.</h2>
          <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" class="right-img" />
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
            tincidunt arcu. Proin in leo fringilla, vestibulum mi porta,
            faucibus felis. Integer pharetra est nunc, nec pretium nunc
            pretium ac.
          </p>
        </article>
      </section>
      <aside id="sidebar">
        <div class="widget-box">
          <h3 class="title">Widget Header</h3>
          <ul>
            <li><a href="#">Widget Link</a></li>
            <li><a href="#">Widget Link</a></li>
            <li><a href="#">Widget Link</a></li>
            <li><a href="#">Widget Link</a></li>
            <li><a href="#">Widget Link</a></li>
          </ul>
        </div>
        <div class="widget-box">
          <h3 class="title">Widget Text</h3>
          <p>
            Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
            tincidunt arcu. Proin in leo fringilla, vestibulum mi porta,
            faucibus felis. Integer pharetra est nunc, nec pretium nunc
            pretium ac.
          </p>
        </div>
      </aside>
    </div>
    <footer>
      <p>
        &copy; 2022 - Universitas Pelita Bangsa
      </p>
    </footer>
  </div>

  <!-- Optional JavaScript; choose one of the two! -->

  <!-- Option 1: Bootstrap Bundle with Popper -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
    crossorigin="anonymous"></script>

  <!-- Option 2: Separate Popper and Bootstrap JS -->
  <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
</body>

</html>
