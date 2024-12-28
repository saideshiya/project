# Project Responsive Web Design using Bootstrap
# Date: 
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  <style>
    .hero {
      background-color: #b35c5c;
      text-align: center;
      padding: 4rem 0;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
      margin-bottom: 1rem;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem 0;
    }
  </style>
</head>
<body style="background-color: antiquewhite;">
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container">
    <a class="navbar-brand" href="#">Dribbble Clone</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
        <li class="nav-item"><a class="nav-link" href="#gallery">Gallery</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<section class="hero">
  <div class="container">
    <h1>Discover Creative Work</h1>
    <p>Join the world's leading platform for showcasing and discovering creative work.</p>
    <a href="#gallery" class="btn btn-primary btn-lg">Explore Gallery</a>
  </div>
</section>

<section id="gallery" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Gallery</h2>
    <div class="row">
      <div class="col-md-4">
        <img src="c:\Users\admin\Downloads\123.jpeg" alt="Gallery Image" class="gallery">
      </div>
      <div class="col-md-4">
        <img src="c:\Users\admin\Downloads\234.jpeg" alt="Gallery Image" class="gallery">
      </div>
      <div class="col-md-4">
        <img src="c:\Users\admin\Downloads\345.jpeg" alt="Gallery Image" class="gallery">
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="container">
    <p>&copy; 2024 Dribbble Clone. All rights reserved.SAI DESHIYA</p>
  </div>
</footer>
</body>
</html>
```
# OUTPUT:

![Screenshot (141)](https://github.com/user-attachments/assets/e6cd6f09-96f2-4764-a63a-ced9995118ac)


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
