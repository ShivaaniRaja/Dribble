# Project Responsive Web Design using Bootstrap
## Date:30-12-24

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
        <a class="navbar-brand" href="#">Dribbble</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav me-auto">
                <li class="nav-item">
                    <a class="nav-link active" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Shots</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Designers</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Teams</a>
                </li>
            </ul>
            <div class="d-flex">
                <a href="#" class="btn btn-outline-light me-2">Log In</a>
                <a href="#" class="btn btn-light">Sign Up</a>
            </div>
        </div>
    </div>
</nav>

<!-- Content Section -->
<div class="container my-5">
    <div class="row row-cols-1 row-cols-md-3 g-4">
        <!-- Card 1 -->
        <div class="col">
            <div class="card h-100">
                <img src="saloon.jpg" class="card-img-top" alt="Vurve Saloon">
                <div class="card-body">
                    <h5 class="card-title">VURVE SALOON</h5>
                    <p class="card-text">Best Classic Saloon</p>
                </div>
            </div>
        </div>
        <!-- Card 2 -->
        <div class="col">
            <div class="card h-100">
                <img src="botique.jpg" class="card-img-top" alt="She Boutique">
                <div class="card-body">
                    <h5 class="card-title">SHE BOTIQUE</h5>
                    <p class="card-text">New Look With Royal Collections</p>
                </div>
            </div>
        </div>
        <!-- Card 3 -->
        <div class="col">
            <div class="card h-100">
                <img src="jewellery.jpg" class="card-img-top" alt="VBJ Jewellers">
                <div class="card-body">
                    <h5 class="card-title">VBJ JEWELLERS</h5>
                    <p class="card-text">Temple set jewellery with perfect finishing</p>
                </div>
            </div>
        </div>
        <!-- Card 4 -->
        <div class="col">
            <div class="card h-100">
                <img src="sports.jpg" class="card-img-top" alt="Decathlon">
                <div class="card-body">
                    <h5 class="card-title">DECATHLON</h5>
                    <p class="card-text">Spirit Of A Sports Man</p>
                </div>
            </div>
        </div>
        <!-- Card 5 -->
        <div class="col">
            <div class="card h-100">
                <img src="book.jpg" class="card-img-top" alt="The Barnes Book Store">
                <div class="card-body">
                    <h5 class="card-title">THE BARNES BOOK STORE</h5>
                    <p class="card-text">Time To Build Your Knowledge</p>
                </div>
            </div>
        </div>
        <!-- Card 6 -->
        <div class="col">
            <div class="card h-100">
                <img src="cake shop.jpg" class="card-img-top" alt="FB Cakes">
                <div class="card-body">
                    <h5 class="card-title">FB CAKES</h5>
                    <p class="card-text">Cut And Eat In Your Own Tastes</p>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- Footer -->
<footer class="bg-dark text-light text-center py-3">
    <p>Designed and developed by <strong>R.SHIVAANI (24007075)</strong></p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2024-12-30 140004.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
