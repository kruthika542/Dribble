<img width="1443" height="733" alt="Screenshot 2025-10-16 121329" src="https://github.com/user-attachments/assets/1b5de954-ccde-4beb-957a-eac172a8353b" /># Project Responsive Web Design using Bootstrap
## Date:16-10-2025

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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dribbble Simple Clone - hemapriya</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .navbar-dark-custom { background-color: #e82121; }
    .btn-dribbble { background-color: #b34cea; color: rgb(205, 47, 47); border: none; }
    .cta-banner { background-color: #af1616; padding: 30px 0; text-align: center; }
    .shot-card-img { border-radius: 8px; width: 100%; height: 200px; object-fit: cover; }
    .app-footer { background-color: #57a4f0; border-top: 1px solid #48cfdc; padding: 20px 0; text-align: center; }
  </style>
</head>
<body>

  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-lg navbar-dark-custom py-3">
    <div class="container">
      <a class="navbar-brand fw-bold fs-4 text-light" href="#">dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item"><a class="nav-link text-white-50" href="#">shots</a></li>
          <li class="nav-item"><a class="nav-link text-white-50" href="#">designers</a></li>
          <li class="nav-item"><a class="nav-link text-white-50" href="#">teams</a></li>
          <li class="nav-item"><a class="nav-link text-white-50" href="#">community</a></li>
          <li class="nav-item"><a class="nav-link text-white-50" href="#">jobs</a></li>
        </ul>
        <a href="#" class="btn btn-outline-light btn-sm me-2">Sign up</a>
        <a href="#" class="btn btn-dribbble btn-sm">Sign in</a>
      </div>
    </div>
  </nav>

  <!-- CTA BANNER -->
  <div class="cta-banner mb-4">
    <div class="container">
      <h4 class="fw-bold mb-2">What are you working on? Dribbble is the community for showcasing creative work.<a href="#" class="btn btn-light border me-2">Learn more</a>
      <a href="#" class="btn btn-dribbble">Join Now</a></h4>
      
      
    </div>
  </div>

  <!-- IMAGE GRID -->
  <div class="container mb-5">
    <div class="d-flex justify-content-between align-items-center mb-4">
      <h5 class="fw-bold">I DESIGNED SOMETHING SPECIAL</h5>
    </div>

    <div class="row row-cols-2 row-cols-md-3 row-cols-lg-5 g-4">

      <div class="col">
        <img src="phone1.jpg" class="shot-card-img" alt="Design 1">
        <p class="fw-semibold mb-0 mt-2">hemapriya Design 1</p>
        <span class="text-muted small">6.2k Likes | 340 Views</span>
      </div>

      <div class="col">
        <img src="phone2.jpg" class="shot-card-img" alt="Design 2">
        <p class="fw-semibold mb-0 mt-2"> hemapriyaDesign 2</p>
        <span class="text-muted small">800 Likes | 500 Views</span>
      </div>

      <div class="col">
        <img src="phone3.jpg" class="shot-card-img" alt="Design 3">
        <p class="fw-semibold mb-0 mt-2">hemapriya Design 3</p>
        <span class="text-muted small">5k Likes | 200 Views</span>
      </div>

      <div class="col">
        <img src="phone4.jpg" class="shot-card-img" alt="Design 4">
        <p class="fw-semibold mb-0 mt-2">hemapriya Design 4</p>
        <span class="text-muted small">6.4k Likes | 900 Views</span>
      </div>

      <div class="col">
        <img src="phone5.jpg" class="shot-card-img" alt="Design 5">
        <p class="fw-semibold mb-0 mt-2">hemapriya Design 5</p>
        <span class="text-muted small">9.3k Likes | 1000 Views</span>
      </div>

      <div class="col">
        <img src="phone6.jpg" class="shot-card-img" alt="Design 6">
        <p class="fw-semibold mb-0 mt-2">hemapriya Design 6</p>
        <span class="text-muted small">99k Likes | 1111 Views</span>
      </div>

      <div class="col">
        <img src="phone7.jpg" class="shot-card-img" alt="Design 7">
        <p class="fw-semibold mb-0 mt-2">hemapriya Design 7</p>
        <span class="text-muted small">8.5k Likes | 333 Views</span>
      </div>

      <div class="col">
        <img src="phone8.jpg" class="shot-card-img" alt="Design 8">
        <p class="fw-semibold mb-0 mt-2">hemapriya Design 8</p>
        <span class="text-muted small">1.11k Likes | 777 Views</span>
      </div>

      <div class="col">
        <img src="phone9.jpg" class="shot-card-img" alt="Design 9">
        <p class="fw-semibold mb-0 mt-2">hemapriya Design 9</p>
        <span class="text-muted small">5k Likes | 888 Views</span>
      </div>

      <div class="col">
        <img src="phone10.jpg" class="shot-card-img" alt="Design 10">
        <p class="fw-semibold mb-0 mt-2">hemapriya Design 10</p>
        <span class="text-muted small">9k Likes | 555 Views</span>
      </div>

    </div>
  </div>

  <!-- FOOTER -->
  <footer class="app-footer">
    <div class="container">
      <p class="text-muted mb-0 small">
        © 2025 Dribbble Simple Clone | Designed by <strong>HEMAPRIYA S(25017270)</strong>
      </p>
    </div>
  </footer>

  
</body>
</html>
```

## OUTPUT:

![Uploading Screenshot 2025-10-16 121329.png…]()




## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
