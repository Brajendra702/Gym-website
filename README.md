<!doctype html>
<html lang="en">

<head>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="style.css">

  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">

  <title>Gym website</title>
  <!----------- Navbar code start from here----------->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01"
        aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
        <a class="navbar-brand" href="#"><b>FitMind</b></a>
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About Us</a>
          </li>
        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
</head>

<body>
  <!-------------Cousral code is start from here-------->
  <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="photo/first.jpg" width="100%" height="300" alt="...">
      </div>
      <div class="carousel-item">
        <img src="photo/second.jpg" width="100%" height="300" alt="...">
      </div>
      <div class="carousel-item">
        <img src="photo/third.jpg" width="100%" height="300" alt="...">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </button>
  </div><br>
  <!-------- cards code start from here----->
  <h3>
    <Center>Our free Training Programs</Center>
  </h3><br>
  <div class="row row-cols-1 row-cols-md-3 g-4">
    <div class="col">
      <div class="card h-100">
        <img src="photo/card2.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Yoga For All</h5>
          <button type="button" class="btn btn-outline-success">Join Now</button>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card h-100">
        <img src="photo/card3.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Fitness training with personal coach</h5>
          <button type="button" class="btn btn-outline-success">Join Now</button>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card h-100">
        <img src="photo/card1.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Booty workout</h5>
          <button type="button" class="btn btn-outline-success">Join Now</button>
        </div>
      </div>
    </div>
  </div>
  <br>
  <!-----------Grid cards-->
  <h3>
    <center>Paid Programs</center>
  </h3><br>
  <div class="row row-cols-1 row-cols-md-3 g-4">
    <div class="col">
      <div class="card h-100">
        <img src="photo/healthy food.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Proteins and Suppliments</h5>
          <button type="button" class="btn btn-outline-success">Buy Now</button>
          <button type="button" class="btn btn-outline-info">Preview</button>
          <p class="card-text">Get the all suppliments products at very low price and free training of 1 week</p>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card h-100">
        <img src="photo/fat loss.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Fat Loss program</h5>
          <button type="button" class="btn btn-outline-success">Buy Now</button>
          <button type="button" class="btn btn-outline-info">Preview</button>
          <p class="card-text">20 Days extreme fat loss workout for all </p>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="card h-100">
        <img src="photo/weight gain.jpg" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">30 Days Weight gain plan</h5>
          <button type="button" class="btn btn-outline-success">Buy Now</button>
          <button type="button" class="btn btn-outline-info">Preview</button>
          <p class="card-text">We are providing full day diet plan for 30days inculding veg
            and non-veg diet for all age groups.</p>
        </div>
      </div>
    </div>
  </div><br>
  <!----------------Health Club section---------->
  <h3 class="health">OUR HEALTH CLUBS</h3>
  <p class="content">Push your fitness further with our<br>
    mix of facilities and we'll support<br>
    you with advice aon new and<br> better ways to train.</p>
  <br><br>
  <!----------------- user details forms--------------------------->
  <h3>LIVE STREAM OUR<br>
    FITNESS CLASSES</h3>
  <form>
    <div class="row">
      <div class="col">
        <input type="text" class="form-control" placeholder="First name"><br>
        <input type="text" class="form-control" placeholder="Last name"><br>
        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp"
          placeholder="Enter email">
        <input type="checkbox" class="form-check-input" id="exampleCheck1">
        <label class="form-check-label" for="exampleCheck1">Check me out</label>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </div>
  </form><br>
  <!---------------Footer code is start from here-->
  <footer class="footer-area footer--light">
    <div class="footer-big">
      <!-- start .container -->
      <div class="container">
        <div class="row">
          <div class="col-md-3 col-sm-12">
            <div class="footer-widget">
              <div class="widget-about">
                <ul class="contact-details">
                  <li>
                    <span class="icon-earphones"></span> Call Us:
                    <a href="tel:344-755-111">7772936369</a>
                  </li>
                  <li>
                    <span class="icon-envelope-open"></span>
                    <a href="mailto:vijendras452@gmail.com">vijendras452@gmail.com</a>
                  </li>
                </ul>
              </div>
            </div>
            <!-- Ends: .footer-widget -->
          </div>
          <!-- end /.col-md-4 -->
          <div class="col-md-3 col-sm-4">
            <div class="footer-widget">
              <div class="footer-menu footer-menu--1">
                <h4 class="footer-widget-title">Popular Category</h4>
                <ul>
                  <li>
                    <a href="#">Wordpress</a>
                  </li>
                  <li>
                    <a href="#">Plugins</a>
                  </li>
                  <li>
                    <a href="#">Joomla Template</a>
                  </li>
                  <li>
                    <a href="#">Admin Template</a>
                  </li>
                  <li>
                    <a href="#">HTML Template</a>
                  </li>
                </ul>
              </div>
              <!-- end /.footer-menu -->
            </div>
            <!-- Ends: .footer-widget -->
          </div>
          <!-- end /.col-md-3 -->

          <div class="col-md-3 col-sm-4">
            <div class="footer-widget">
              <div class="footer-menu">
                <h4 class="footer-widget-title">Our Company</h4>
                <ul>
                  <li>
                    <a href="#">About Us</a>
                  </li>
                  <li>
                    <a href="#">How It Works</a>
                  </li>
                  <li>
                    <a href="#">Contact Us</a>
                  </li>
                  <li>
                    <a href="#">Plan &amp; Pricing</a>
                  </li>
                  <li>
                    <a href="#">Blog</a>
                  </li>
                </ul>
              </div>
              <!-- end /.footer-menu -->
            </div>
            <!-- Ends: .footer-widget -->
          </div>
          <!-- end /.col-lg-3 -->

          <div class="col-md-3 col-sm-4">
            <div class="footer-widget">
              <div class="footer-menu no-padding">
                <h4 class="footer-widget-title">Help Support</h4>
                <ul>
                  <li>
                    <a href="#">Customer support</a>
                  </li>
                  <li>
                    <a href="#">Terms & Conditions</a>
                  </li>
                  <li>
                    <a href="#">Support Policy</a>
                  </li>
                  <li>
                    <a href="#">Refund Policy</a>
                  </li>
                  <li>
                    <a href="#">FAQs</a>
                  </li>

                </ul>
              </div>
              <!-- end /.footer-menu -->
            </div>
            <!-- Ends: .footer-widget -->
          </div>
          <!-- Ends: .col-lg-3 -->

        </div>
        <!-- end /.row -->
      </div>
      <!-- end /.container -->
    </div>
    <!-- end /.footer-big -->

    <div class="mini-footer">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="copyright-text">
              <p>© 2021
                <a href="#">Fitness World</a>. All rights reserved. Created by
                <a href="#">Brajendra</a>
              </p>
            </div>

            <div class="go_top">
              <span class="icon-arrow-up"></span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
  <!-- Optional JavaScript; choose one of the two! -->

  <!-- Option 1: Bootstrap Bundle with Popper -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf"
    crossorigin="anonymous"></script>

  <!-- Option 2: Separate Popper and Bootstrap JS -->
  <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js" integrity="sha384-SR1sx49pcuLnqZUnnPwx6FCym0wLsk5JZuNx2bPPENzswTNFaQU1RDvt3wT4gWFG" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.min.js" integrity="sha384-j0CNLUeiqtyaRmlzUHCPZ+Gy5fQu0dQ6eZ/xAww941Ai1SxSY+0EQqNXNE6DZiVc" crossorigin="anonymous"></script>
    -->
</body>

</html>
