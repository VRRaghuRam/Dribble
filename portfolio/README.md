# Project Responsive Web Design using Bootstrap
## Date:25/12/2024

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
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

<!-- Navigation Bar -->
<nav class="navbar navbar-expand-lg navbar-danger bg-warning">
    <div class="container">
        <a class="navbar-brand" href="#">Dribbble Clone</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#">Inspiration</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Jobs</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Learn</a>
                </li>
                <li class="nav-item">
                    <a class="btn btn-primary" href="#">Sign Up</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<section class="py-5 text-center bg-secondary">
    <div class="container">
        <h1 class="display-4">APPLE PRODUCTS</h1>
        <p class="lead">Explore creative portfolios, find inspiration, and showcase your work.</p>
        <a href="#" class="btn btn-primary btn-lg">Explore Work</a>
    </div>
</section>

<!-- Featured Work Section -->
<section class="py-5">
    <div class="container">
        <h2 class="text-center mb-4">Featured Work</h2>
        <div class="row g-4">
            <div class="col-md-4">
                <div class="card">
                    <img src="dribble.png" class="card-img-top" alt="Sample Work">
                    <div class="card-body">
                        <h5 class="card-title">IPHONE 16 PRO MAX</h5>
                        
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="dribble 2.png" class="card-img-top" alt="Sample Work">
                    <div class="card-body">
                        <h5 class="card-title">MACBOOK</h5>
                        
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="original-7f0e79e19d4351f38d928f6c4be60827.png" class="card-img-top" alt="Sample Work">
                    <div class="card-body">
                        <h5 class="card-title">AIRPODES</h5>
                        
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Footer -->
<footer class="py-4 bg-dark text-light">
    <div class="container text-center">
        <p class="mb-0">&copy; 2024 Dribbble Clone. All rights reserved.
            <br>Designed & Created by V.RAGHU RAM.
        </p>
    </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```


## OUTPUT:
![alt text](<raghu/static/Screenshot (45).png>)
![alt text](<raghu/static/Screenshot (46).png>)




## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.