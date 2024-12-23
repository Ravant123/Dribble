# Project Responsive Web Design using Bootstrap
## Date:23-12-2024

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
index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ravant's project - Home</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        /* Custom CSS for interactive grid */
        .card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
        }

        .card img {
            height: 200px;
            object-fit: cover;
        }

        .navbar {
            background-color: #2a1919;
        }

        .navbar a {
            color: #fff;
            transition: color 0.3s ease;
        }

        .navbar a:hover {
            color: #f8c146;
        }

        footer {
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="index.html">Ravant's Project</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active" href="index.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="explore.html">Explore</a></li>
                    <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="bg-dark text-white text-center py-5">
        <div class="container">
            <h1>Discover Stunning Free Photos</h1>
            <p class="lead">Browse and download amazing images from talented creators worldwide.</p>
            <a href="explore.html" class="btn btn-warning btn-lg">Start Exploring</a>
        </div>
    </header>

    <!-- Interactive Grid Section -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Popular Photos</h2>
            <div class="row g-4">
                <!-- Card 1 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="1.webp" class="card-img-top" alt="Popular 1">
                        <div class="card-body">
                            <h5 class="card-title">SUPERHEROES</h5>
                            <p class="card-text">This is a beautiful image shared by a talented creator.</p>
                        </div>
                    </div>
                </div>
                <!-- Card 2 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="2.webp" class="card-img-top" alt="Popular 2">
                        <div class="card-body">
                            <h5 class="card-title">SUPERHEROES</h5>
                            <p class="card-text">An inspiring shot capturing the essence of creativity.</p>
                        </div>
                    </div>
                </div>
                <!-- Card 3 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="3.webp" class="card-img-top" alt="Popular 3">
                        <div class="card-body">
                            <h5 class="card-title">SUPERHEROES</h5>
                            <p class="card-text">A stunning perspective that will leave you mesmerized.</p>
                        </div>
                    </div>
                </div>
                <!-- Card 4 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="4.webp" class="card-img-top" alt="Popular 4">
                        <div class="card-body">
                            <h5 class="card-title">SUPERHEROES</h5>
                            <p class="card-text">An incredible photo showcasing the beauty of nature.</p>
                        </div>
                    </div>
                </div>
                <!-- Card 5 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="5.webp" class="card-img-top" alt="Popular 5">
                        <div class="card-body">
                            <h5 class="card-title">SUPERHEROES</h5>
                            <p class="card-text">Explore the unique textures and colors of this shot.</p>
                        </div>
                    </div>
                </div>
                <!-- Card 6 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="6.webp" class="card-img-top" alt="Popular 6">
                        <div class="card-body">
                            <h5 class="card-title">SUPERHEROES</h5>
                            <p class="card-text">A visually striking photo for creative inspiration.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center py-4">
        <p>Designed by S.RAVANT VIGNESH © 2024</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ravant's Project - About</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .navbar {
            background-color: #333;
        }

        .navbar a {
            color: #fff;
            transition: color 0.3s ease;
        }

        .navbar a:hover {
            color: #f8c146;
        }

        footer {
            background-color: #333;
            color: #fff;
        }

        .about-section {
            background: #f8f9fa;
            padding: 60px 20px;
        }

        .about-text {
            font-size: 1.1rem;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="index.html">Ravant's Project</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="explore.html">Explore</a></li>
                    <li class="nav-item"><a class="nav-link active" href="about.html">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- About Section -->
    <section class="about-section">
        <div class="container text-center">
            <h2 class="mb-4">About Us</h2>
            <p class="about-text">
                Pexels Clone is your go-to platform for discovering and sharing amazing free photos from creators around the world. Our mission is to make visual content accessible to everyone while celebrating creativity and talent.
            </p>
            <img src="https://via.placeholder.com/800x400" alt="About Us" class="img-fluid mt-4">
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center py-4">
        <p>Designed by S.Ravant Vignesh © 2024</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


explore.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ravant's project - Explore</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .card:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
        }

        .card img {
            height: 200px;
            object-fit: cover;
        }

        .navbar {
            background-color: #333;
        }

        .navbar a {
            color: #fff;
            transition: color 0.3s ease;
        }

        .navbar a:hover {
            color: #f8c146;
        }

        footer {
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="index.html">Ravant's Project</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link active" href="explore.html">Explore</a></li>
                    <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Explore Section -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Explore Our Collection</h2>
            <div class="row g-4">
                <!-- Dynamically populate with similar image cards as in Home -->
                <!-- Add 9 example cards -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="6.webp" class="card-img-top" alt="Explore Image 1">
                        <div class="card-body">
                            <h5 class="card-title">SUPERHEROES</h5>
                            <p class="card-text">beautiful gallery about marvels</p>
                        </div>
                    </div>
                </div>
                <!-- Repeat similar cards -->
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>DESIGNED BY S.RAVANT VIGNESH


contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ravant's Project - Contact</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        .navbar {
            background-color: #333;
        }

        .navbar a {
            color: #fff;
            transition: color 0.3s ease;
        }

        .navbar a:hover {
            color: #f8c146;
        }

        footer {
            background-color: #333;
            color: #fff;
        }

        .contact-section {
            background: #f8f9fa;
            padding: 60px 20px;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="index.html">Ravant's Project</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="index.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="explore.html">Explore</a></li>
                    <li class="nav-item"><a class="nav-link" href="about.html">About</a></li>
                    <li class="nav-item"><a class="nav-link active" href="contact.html">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Contact Section -->
    <section class="contact-section">
        <div class="container">
            <h2 class="text-center mb-4">Get in Touch</h2>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Your Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Enter your name">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email address</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email">
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" rows="4" placeholder="Write your message here"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center py-4">
        <p>Designed by S.RAVANT VIGNESH © 2024</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:

![alt text](<Screenshot (105).png>)
![alt text](<Screenshot (106).png>)
![alt text](<Screenshot (107).png>)
![alt text](<Screenshot (108).png>)
![alt text](<Screenshot (109).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
