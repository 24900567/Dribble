# Project Responsive Web Design using Bootstrap
## Date:25.12.2024

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
    <title>Icart</title>
    <link rel="stylesheet" href="bg.jpg">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Icart</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Account & Lists</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Help</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Header Section -->
    <header>
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h1>Welcome to Icart</h1>
                </div>
                <div class="col-md-6">
                    <form>
                        <input type="search" placeholder="Search...">
                        <button type="submit">Search</button>
                    </form>
                </div>
            </div>
        </div>
    </header>

    <!-- Main Section -->
    <main>
        <div class="container">
            <div class="row">
                <div class="col-md-3">
                    <h2>Categories</h2>
                    <ul>
                        <li><a href="#">Electronics</a></li>
                        <li><a href="#">Fashion</a></li>
                        <li><a href="#">Home & Kitchen</a></li>
                    </ul>
                </div>
                <div class="col-md-9">
                    <h2>Products</h2>
                    <div class="row">
                        <div class="col-md-4">
                            <div class="card">
                                <img src="iphone.jpg" alt="product image">
                                <div class="card-body">
                                    <h5 class="card-title">iPhone 16 Pro Max</h5>
                                    <p class="card-text">1,95,000</p>
                                    <a href="#" class="btn btn-primary">Add to Cart</a>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-4">
                            <div class="card">
                                <img src="kitchen accesarry.jpg" alt="Product Image">
                                <div class="card-body">
                                    <h5 class="card-title">Kitchen Accessary</h5>
                                    <p class="card-text">2000</p>
                                    <a href="#" class="btn btn-primary">Add to Cart</a>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-4">
                            <div class="card">
                                <img src="fasion asseary.jpg" alt="Product Image">
                                <div class="card-body">
                                    <h5 class="card-title">Fasion Accessary</h5>
                                    <p class="card-text">9000</p>
                                    <a href="#" class="btn btn-primary">Add to Cart</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-md-4">
                    <h2>About Us</h2>
                    <p>Conditions of Use & Sale<br>
                        Privacy Notice<br>
                        Interest-Based Ads<br>
                        © 1996-2024, Amazon.com, Inc. or its affiliates</p>
                    
                </div>
                <div class="col-md-4">
                    <h2>Help & Support</h2>
                    <p>Your Account<BR>
                        Returns Centre<br>
                        Recalls and Product Safety Alerts<br>
                        100% Purchase Protection<br>
                        Amazon App Download<br>
                        Help</p>
                </div>
                <div class="col-md-4">
                    <h2>Follow Us</h2>
                    <p>Connect with Us<br>
                        Facebook<br>
                        Twitter<br>
                        Instagram.</p>
                </div>
            </div>
        </div>
    </footer>

    <script src="(link unavailable)"></script>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2024-12-25 063130.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
