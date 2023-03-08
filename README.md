TinDog Starting Files
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>tindog</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat&family=Ubuntu&display=swap" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
  
  <link rel="stylesheet" href="css/styles.css">
  
  <script src="https://kit.fontawesome.com/d46a75c4a9.js" crossorigin="anonymous"></script>
 
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js" integrity="sha384-oBqDVmMz9ATKxIep9tiCxS/Z9fNfEXiDAYTujMAeBAsjFuCZSmKbSSUnQlmh/jp3" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js" integrity="sha384-mQ93GR66B00ZXjt0YO5KlohRA5SY2XofN4zfuZxLkoj1gXtW8ANNCe9d5Y3eG5eD" crossorigin="anonymous"></script>
</head>

<body>

  <section id="title">
    <div class="container-fluid">
    <!-- Nav Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark">
    <a class="navbar-brand" href="">tindog</a>
    <button class="navbar-toggler"type="button" data-bs-toggle="collapse">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
      <ul class="navbar-nav ms-auto">
        <il class="nav-item">
          <a class="nav-link" href="#footer">Contact</a>
        </il>
        <li class="nav-item">
          <a class="nav-link" href="#pricing">Pricing</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#cta">Download</a>
        </li>
      </ul>
    </div>
  </nav>



    <!-- Title -->

  <div class="row">

    <div class="col-lg-6">
      <h1 class="big-heading">Meet new and interesting dogs nearby.</h1>
      <button type="button" class="btn btn-dark btn-lg download-button"><i class="fa-brands fa-apple"></i> Download</button>
      <button type="button" class="btn btn-outline-light btn-lg"><i class="fa-brands fa-google-play"></i> Download</button>
    </div>
  
   
    <div class="col-lg-6">
      <img class="title-image" style="transform: rotate(25deg)" src="images/iphone6.png" alt="iphone-mockup">
    </div>
  </div>
    </div>
  </section>


  <!-- Features -->

<section class="white-section" id="features">

<div class="container-fluid">
<div class="row"> 
  <div class="feature-box col-lg-4">
    <i class="icon fa-solid fa-circle-check fa-4x"></i>
    <h3 class="feature-title"> Easy to use.</h3>
    <p style="color:#818181">So easy to use, even your dog could do it.</p>
  </div>
  <div class="feature-box col-lg-4">
    <i class="icon fa-solid fa-bullseye fa-4x"></i>
    <h3 class="feature-title">Elite Clientele.</h3>
    <p style=>We have all the dogs, the greatest dogs.</p>
  </div>
  <div class="feature-box col-lg-4">
    <i class="icon fa-solid fa-heart fa-4x"></i>
    <h3 class="feature-title">Guaranteed to work.</h3>
    <p style="color:#818181">Find the love of your dog's life or your money back.</p>
    </div>
</div> 
</div>  
</section>


  <!-- Testimonials -->

  <section class="colored-section" id="testimonials">
    
    <div id="testimonial-carousel" class="carousel slide" data-bs-ride="false">
      <div class="carousel-inner">
        <div class="carousel-item active container-fluid">
          <h2 class="testimonial-text">I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
          <img class="testimonial-image"src="images/dog-img.jpg" alt="dog-profile">
          <em>Pebbles, New York</em>
        
    </div>
        <div class="carousel-item container-fluid">
          <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
          <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
          <em>Beverly, Illinois</em>
          
        </div>
        
      </div>
      <a class="carousel-control-prev"  type="button" data-bs-target= "#testimonial-carousel" data-bs-slide="prev">
        <span class="carousel-control-prev-icon"></span>
      </a>
      <a class="carousel-control-next"  type="button" data-bs-target= "#testimonial-carousel" data-bs-slide="next">
        <span class="carousel-control-next-icon"></span>
      </a>
      
    </div>

    

  </section>


  <!-- Press -->

  <section class="colored-section" id="press">
    <img class= "press-logo" src="images/techcrunch.png" alt="tc-logo">
    <img class= "press-logo" src="images/tnw.png" alt="tnw-logo">
    <img class= "press-logo" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class= "press-logo" src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section class="white-section" id="pricing">

    <h2 class="section-heading">A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>

<div class="row">
  
  <div class="pricing-column col-lg-4 col-md-6"> 
    <div class="card">
      <div class="card-header">
        <h3>Chihuahua</h3>
      </div>
      <div class="card-body">
       <h2 class="price-text">Free</h2>
       <p>5 Matches Per Day</p>
       <p>10 Messages Per Day</p>
       <p>Unlimited App Usage</p>
       <button type="button" class="btn btn-outline-dark">Sign Up for free</button>
      </div>
    </div>
  </div>

  <div class="pricing-column col-lg-4 col-md-6">
    <div class="card">
      <div class="card-header">
        <h3>Labrador</h3>
      </div>
      <div class="card-body">
        <h2 class="price-text">$49 / mo</h2>
        <p>Unlimited Matches</p>
        <p>Unlimited Messages</p>
        <p>Unlimited App Usage</p>
        <button type="button" class="btn btn-dark">Sign Up</button>
      </div>
    </div>
  </div>
  <div class="pricing-column col-lg-4">
    <div class="card">
      <div class="card-header">
        <h3>Mastiff</h3>
      </div>
      <div class="card-body">
        <h2 class="price-text">$99 / mo</h2>
        <p>Pirority Listing</p>
        <p>Unlimited Matches</p>
        <p>Unlimited Messages</p>
        <p>Unlimited App Usage</p>
        <button type="button" class="btn btn-dark">Sign Up</button> 
      </div>
    </div>
  </div>
</div>
   
    


    
    


    
    

  </section>


  <!-- Call to Action -->

  <section class="colored-section" id="cta">
  <div class="container-fluid">

    <h3 class="big-heading">Find the True Love of Your Dog's Life Today.</h3>
    <button type="button" class="btn btn-dark btn-lg download-button"><i class="fa-brands fa-apple"></i> Download</button>
    <button type="button" class="btn btn-outline-light btn-lg"><i class="fa-brands fa-google-play"></i> Download</button>
  </div>
  </section>


  <!-- Footer -->

  <footer class="white-section" id="footer">
    <div class="container-fluid">
    <i class="social_media_icon fa-brands fa-twitter"></i>
    <i class="social_media_icon fa-brands fa-facebook"></i>
    <i class="social_media_icon fa-brands fa-instagram"></i>
    <i class="social_media_icon fa-solid fa-envelope"></i>
    <p>© Copyright TinDog</p>
    
  </div>
  </footer>


</body>

</html>
