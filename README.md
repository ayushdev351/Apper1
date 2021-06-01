# Apper
<!DOCTYPE html>
<html lang="en" dir="ltr">

<!-- Head is a container for meta data. Metadata typically define the document title, character set, styles, scripts,and other meta information. -->

<head>
  <!-- UTF is used to define the character decoding of our HTML code -->
  <meta charset="utf-8">
  <meta name="keywords" content="site keywords">
  <meta name="description" content="landing page">
  <!-- Viewport is the size of the display screen -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0, shrink-to-fit=no">
  <!-- Title is displayed on the tab -->
  <title>Apper</title>
  <!-- Used to preload the fonts from google font -->
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat&family=Ubuntu:wght@300&display=swap">
  <!-- Linking BOotstrap 5 -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">
  <!-- Linking main CSS file -->
  <link rel="stylesheet" href="project.css">
  <!-- Linking and Loading favicon image -->
  <link rel="icon" href="">
  <!-- Linking icons from FontAwesome Library -->
  <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous" />
  <!-- JS script for working of some components of Bootstrap -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js" integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf" crossorigin="anonymous"></script>
</head>

<!-- All the main content which is to be displayed is written inside the body -->

<body>

  <section id="Navigation">



    </div>
    <div class="Navbar">
      <!-- Navbar can be made by using Bootstrap nav classes as follows -->
      <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container-fluid">
          <!-- Brand refers to the App icon or website icon or brand icon -->
          <a class="brand-icon navbar-brand" href="#">
            <i class=" fab fa-autoprefixer"></i>pper
            <!-- Used from FontAwesomeLibrary -->
          </a>
          <!-- Toggle button for Responsive Behaviour -->
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarToggler" aria-controls="navbarToggler" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarToggler">
            <!-- List of Navbar items -->
            <ul class="navbar-nav ms-auto">
              <!-- ms-auto is used to allign nav items to right -->
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#Home">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#feature">Features</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#Screenshots">Screenshots</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Video</a>
              </li>
              <li class="nav-item">
                <div class="dropdown show">
                  <a class="nav-link dropdown-toggle" data-toggle="dropdown" id="dropdown-menu-link" aria-haspopup="true" aria-expanded="false" href="#pricing">Pricing</a>
                  <div class="dropdown-menu" aria-labelledby="dropdown-menu-link">
                    <a class="dropdown-item" href="#">Basic</a>
                    <a class="dropdown-item" href="#">Advanced</a>
                    <a class="dropdown-item" href="#">Premium</a>
                  </div>
                </div>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#footer">Contact</a>
              </li>
              <li class="nav-item">
                <button class="download-button  btn btn-outline-light" type="button"><i class="fas fa-download"></i> Download</button>
              </li>
            </ul>
          </div>
        </div>
      </nav>

    </div>
  </section>
  <section id="Home">
    </div>
    <div class="Intro-One">
      <div class="row" style="margin:0;">
        <div class="col-lg-6 col-md-8 col-sm-10 col-10">
          <h1 class="Heading">Apper Is A Static Landing Page made by Ayush</h1>
          <p class="Intro-para">Lorem ipsum dolor sit amet, consectetur adipiscing elit Seda sagittis nisl enim, a pulvinar odio rhoncus orem ipsum</p>

          <a href="signup.html" class="button-Intro btn btn-lg btn-outline-light"><i class="fas fa-sign-in-alt"></i> Signup</a>
        </div>

        <div class=" col-lg-6">
          <img class="Intro-img" src="https://themelamp.com/templates/appmela/images/about.png" alt="Intro-img">
        </div>
      </div>
    </div>

    <div class="Intro-two" id="feature">
      <div class="About">
        <h2 class="About-head">About Apper</h2>
        <hr class="horizontal-line" style="height:5px;">
        <p class="About-para">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>

      </div>
      <div class="row" style="margin:0;">
        <div class="feature-col col-lg-4 col-md-4 col-sm-6 col-12">
          <i class="feature-icon fas fa-fighter-jet"></i> <!-- Icon -->
          <h4 class="feature-head">High Speed</h4>
          <p class="feauture-info">consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore</p>
        </div>
        <div class="feature-col col-lg-4 col-md-4 col-sm-6 col-12">
          <i class="feature-icon fas fa-lightbulb"></i><!-- Icon -->
          <h4 class="feature-head">Creative Idea</h4>
          <p class="feauture-info">lorem ipsum consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore</p>
        </div>
        <div class="feature-col col-lg-4 col-md-4 col-sm-6 col-12">
          <i class="feature-icon fas fa-gem"></i><!-- Icon -->
          <h4 class="feature-head">Great Features</h4>
          <p class="feauture-info">consectetur adipisicing elit, sed do eiusmod tempor incididunt ut </p>
        </div>
        <div class="feature-col col-lg-4 col-md-4 col-sm-6 col-12">
          <i class="feature-icon fas fa-pencil-alt"></i><!-- Icon -->
          <h4 class="feature-head">Customisable</h4>
          <p class="feauture-info">consectetur adipisicing elit, do eiusmod tempor incididunt ut labore</p>
        </div>
        <div class="feature-col col-lg-4 col-md-4 col-sm-6 col-12">
          <i class="feature-icon fas fa-mobile"></i><!-- Icon -->
          <h4 class="feature-head">Responsive</h4>
          <p class="feauture-info">consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore sed do</p>
        </div>
        <div class="feature-col col-lg-4 col-md-4 col-sm-6 col-12">
          <i class="feature-icon fas fa-headphones"></i><!-- Icon -->
          <h4 class="feature-head">Easy Support</h4>
          <p class="feauture-info">consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore</p>
        </div>
        <div class="feature-col col-lg-4 col-md-4 col-sm-6 col-12">
          <i class="feature-icon fas fa-coins"></i><!-- Icon -->
          <h4 class="feature-head">Money Value</h4>
          <p class="feauture-info">lorem consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore</p>
        </div>
        <div class="feature-col col-lg-4 col-md-4 col-sm-6 col-12">
          <i class="feature-icon fas fa-laptop-code"></i><!-- Icon -->
          <h4 class="feature-head">Clean Code</h4>
          <p class="feauture-info">consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore</p>
        </div>
        <div class="feature-col col-lg-4 col-md-4 col-sm-6 col-12">
          <i class="feature-icon fas fa-headphones"></i><!-- Icon -->
          <h4 class="feature-head">Best Value</h4>
          <p class="feauture-info">consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore</p>
        </div>
      </div>

    </div>

  </section>
  <hr class="horizontal-line-2" style="height: 5px;">
  <section id="Screenshots">
  <div class="px-4 pt-5 my-5 text-center border-bottom" style="padding-bottom:3%;">
    <h1 class="display-4 fw-bold" style="color: #f72585">Our Best App</h1>
    <div class="col-lg-6 mx-auto">
      <p class="lead mb-4">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.Ut enim ad minim veniam.</p>
      <div class="d-grid gap-2 d-sm-flex justify-content-sm-center mb-5">
        <button type="button" class="btn btn-primary btn-lg px-4 me-sm-3 my-button">Show App</button>
        <button type="button" class="btn btn-outline-secondary btn-lg px-4">Buy App</button>
      </div>
    </div>
    <div class="overflow-hidden" style="max-height: 30vh;">
      <div class="container px-5">
        <img src="https://screenlane.com/media/screenshots/anchor-web-app-screenshot-thumbnail_HeTpiHY.jpg" class="img-fluid border rounded-3 shadow-lg mb-4" alt="Example image" width="700" height="500" loading="lazy">
      </div>
  </div>
  <hr class="horizontal-line-2" style="height: 5px;">
    <div class="container col-xxl-8 px-4 py-5">
     <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
       <div class="col-10 col-sm-8 col-lg-6">
         <img src="https://getbootstrap.com/docs/5.0/examples/heroes/bootstrap-themes.png" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes" width="700" height="500" loading="lazy">
       </div>
       <div class="col-lg-6">
         <h1 class="display-5 fw-bold lh-1 mb-3" style="color: #f72585;">All Apps which we have made</h1>
         <p class="lead" >Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.Ut enim ad minim veniam, quis.Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur</p>
         <div class="d-grid gap-2 d-md-flex justify-content-md-start">
           <button type="button" class="btn btn-info btn-lg px-4 me-md-2 my-info-btn">Explore</button>
         </div>
       </div>
     </div>
   </div>
  </section>
  <hr class="horizontal-line-2" style="height: 5px;">
  <section id="pricing" class="pricing">
    <h1 class="display-4 fw-normal" style="text-align:center; color:#f72585;">Pricing</h1>
      <p class="fs-5 text-muted pricing-text">This is our price section built with Bootstrap Cards. You can select any price which suits or or you can Signup for free. lorem ipsum consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore.</p>
    </div>
    <div class="row row-cols-1 row-cols-md-3 mb-3 text-center">
      <div class="col price-card">
        <div class="card mb-4 rounded-3 shadow-sm my-background">
          <div class="card-header py-3 my-card-head text-white">
            <h4 class="my-0 fw-normal">Free</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">$0<small class="text-muted fw-light">/mo</small></h1>
            <ul class="list-unstyled mt-3 mb-4">
              <li>5 free templates</li>
              <li>No changes</li>
              <li>Email support</li>
              <li>Help center access</li>
            </ul>
            <a href="signup.html" class="w-100 btn btn-lg btn-outline-dark my-card-btn">Signup</a>
          </div>
        </div>
      </div>
      <div class="col price-card">
        <div class="card mb-4 rounded-3 shadow-sm my-background">
          <div class="card-header py-3 my-card-head text-white">
            <h4 class="my-0 fw-normal">Pro</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">$15<small class="text-muted fw-light">/mo</small></h1>
            <ul class="list-unstyled mt-3 mb-4">
              <li>30 free templates</li>
              <li>5 times changes</li>
              <li>Priority email support</li>
              <li>Help center access</li>
            </ul>
            <button type="button" class="w-100 btn btn-lg btn-outline-info my-card-btn">Get started</button>
          </div>
        </div>
      </div>
      <div class="col price-card">
        <div class="card mb-4 rounded-3 shadow-sm my-background">
          <div class="card-header py-3 my-card-head text-white">
            <h4 class="my-0 fw-normal">Enterprise</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">$29<small class="text-muted fw-light">/mo</small></h1>
            <ul class="list-unstyled mt-3 mb-4">
              <li>Unlimited templates</li>
              <li>Unlimited changes</li>
              <li>Phone and email support</li>
              <li>Help center access</li>
            </ul>

            <a href="https://www.instagram.com/ayush_chauhan.ji/" class="w-100 btn btn-lg btn-outline-info my-card-btn">Contact Us</a>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="footer" id="footer">
    <footer class="pt-4 my-md-5 pt-md-5 border-top">
    <div class="row">
      <div class="col-12 col-md">

        <p class="brand-icon"><i class=" fab fa-autoprefixer brand-icon"></i>pper</p>
        <small class="d-block mb-3 text-muted">&copy; Ayush Chauhan 2021</small>
      </div>
      <div class="col-6 col-md">
        <h5>Contact Us</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="https://www.instagram.com/ayush_chauhan.ji/">Instagram</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Facebook</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="https://web.whatsapp.com/">Whatsapp</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="https://iwe.quora.com/?ch=99&share=bb7bf04e&srid=pNXlY">Quora</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Dribble</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Linkedin</a></li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>Resources</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Resource</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Resource name</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Another resource</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Final resource</a></li>
        </ul>
      </div>
      <div class="col-6 col-md">
        <h5>About</h5>
        <ul class="list-unstyled text-small">
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Team</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Locations</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Privacy</a></li>
          <li class="mb-1"><a class="link-secondary text-decoration-none" href="#">Terms</a></li>
        </ul>
      </div>
    </div>
  </footer>
</div>
</section>

</body>

</html>
