# kresz-teszt
PHP 
<!doctype html>
<html lang="hu">

<head>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"
    integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

  <script src="https://ajax.googleapis.com/ajax/Libs/jquery/3-3.1/jquery.min.js"></script>

  <title>Nagy kreszvizsga</title>
</head>

<body>






  <!--Navigáció-->
  <nav class="navbar navbar-expand-md navbar-light bg-light sticky-top">
    <div class="contanier-fluid"></div>
    <!-- Brand -->
    <a class="tablak"><img src="tablak.jpg" width="100" height="50" alt="tablak"></a>

    <!-- Links -->
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link" href="https://net.jogtar.hu/jogszabaly?docid=97500001.kpm">Felkészülés </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="https://www.youtube.com/watch?v=f9hRDUpfLNw">Videok</a>
      </li>

      <!-- Dropdown -->
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
          Menü
        </a>
        <div class="dropdown-menu">
          <a class="dropdown-item" href="kepek.html">Kresz táblák</a>
          <a class="dropdown-item" href="kategoriak.html">Kategóriák</a>
          <a class="dropdown-item" href="#">Link 3</a>
        </div>
      </li>
    </ul>
    <!--kereső-->
    <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
      <form class="form-inline" action="/action_page.php">
        <input class="form-control mr-sm-2" type="text" placeholder="Search">
        <button class="btn btn-success" type="submit">Keresés</button>
      </form>
    </nav>
    <!--Bejelentkezés-->
    <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
      
      <form action="/action_page.php">
        <div class="form-group">
          <label for="email">Email Cím:</label>
          <input type="email" class="form-control" placeholder="Enter email" id="email">
        </div>
        <div class="form-group">
          <label for="pwd">Password:</label>
          <input type="password" class="form-control" placeholder="Add meg az email címed" id="pwd">
        </div>
        <div class="form-group form-check">
          <label class="form-check-label">
            <input class="form-check-input" type="checkbox"> Emlékezz rám
          </label>
        </div>
        <button type="submit" class="btn btn-primary">Küld</button>
      </form>
    </nav>


    <div class="container">
      <h3>Sikeres vizsgát!</h3>
      <p>Tegye probára tudását.</p>
    </div>




    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"
      integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n"
      crossorigin="anonymous"></script>
    </script>>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"
      integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo"
      crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"
      integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6"
      crossorigin="anonymous"></script>


</body>

</html>
