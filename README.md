# Project Responsive Web Design using Bootstrap
## Date:15-10-2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
~~~
design.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dribbble Clone</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Poppins', sans-serif;
    }
    .hero {
      background-color: #f9f9f9;
      padding: 100px 0;
      text-align: center;
    }
    .shots img {
      border-radius: 10px;
      transition: transform 0.3s;
    }
    .shots img:hover {
      transform: scale(1.05);
    }
    footer {
      background-color: #111;
      color: #fff;
      padding: 30px 0;
      text-align: center;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg bg-light shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold text-danger" href="#">DribbbleClone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#">Inspiration</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Sign In</a></li>
          <li class="nav-item">
            <a class="btn btn-danger ms-2" href="#">Sign Up</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1 class="display-5 fw-bold">Discover the world’s top designers & creatives</h1>
      <p class="lead text-muted mb-4">DribbbleClone is where designers share, grow, and get hired.</p>
      <div class="input-group w-50 mx-auto">
        <input type="text" class="form-control" placeholder="Search for design inspiration...">
        <button class="btn btn-danger">Search</button>
      </div>
    </div>
  </section>

  <!-- Shots Gallery -->
  <section class="shots py-5">
    <div class="container">
      <h2 class="text-center fw-bold mb-4">Popular Shots</h2>
      <div class="row g-4">
        <div class="col-md-4 col-sm-6">
          <img src="https://picsum.photos/400/300?random=10" class="img-fluid" alt="shot1">
        </div>
        <div class="col-md-4 col-sm-6">
          <img src="https://picsum.photos/400/300?random=11" class="img-fluid" alt="shot2">
        </div>
        <div class="col-md-4 col-sm-6">
          <img src="https://picsum.photos/400/300?random=12" class="img-fluid" alt="shot3">
        </div>
        <div class="col-md-4 col-sm-6">
          <img src="https://picsum.photos/400/300?random=13" class="img-fluid" alt="shot4">
        </div>
        <div class="col-md-4 col-sm-6">
          <img src="https://picsum.photos/400/300?random=14" class="img-fluid" alt="shot5">
        </div>
        <div class="col-md-4 col-sm-6">
          <img src="https://picsum.photos/400/300?random=15" class="img-fluid" alt="shot6">
        </div>
      </div>
    </div>
  </section>

  <!-- CTA Section -->
  <section class="text-center py-5 bg-light">
    <div class="container">
      <h3 class="fw-bold">Ready to share your designs?</h3>
      <p class="text-muted">Join DribbbleClone today and showcase your creativity to the world.</p>
      <a href="#" class="btn btn-danger btn-lg">Get Started</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>© 2025 DribbbleClone — Built with Bootstrap </p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
~~~

## OUTPUT:
![screenshot1 (2)](https://github.com/user-attachments/assets/6536e528-2a29-4122-be85-5715523c5a2f)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
