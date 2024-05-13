# Project Responsive Web Design using Bootstrap
## Date:09.04.2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
APP.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharma</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
<body>
  <body style="background-color: rgb(25, 104, 119);"></body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">SUSI PHARMA</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home'S</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="developments.html">developments</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact_us.html">Contact_us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="hero d-flex align-items-center justify-content-center text-center py-5 mb-5">
    <div class="container">
      <h1>SUSI HEALTHCARE AND SCIENCE</h1>
      <p class="lead">Analyzing healthcare policies, including recent reforms, insurance coverage expansion, and the impact of government regulations on healthcare delivery.</p>
      <a href="#" class="btn btn-primary btn-lg">MORE INFORMATION</a>
    </div>
  </section>

  <section class="container">
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="our.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">OUR MISSION </h5>
            <p class="card-text">We are dedicated towards understanding customer expectations; identifying and developing opportunities that enhance customer supply chain strategies. Our operating philosophy is to achieve success through a performance-driven culture built on the pursuit of operational excellence, continuous improvement and an uncompromising commitment to quality, customer satisfaction and employee safety.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="usa.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">MODERNISE</h5>
            <p class="card-text">Explore recent advancements and best practices in patient safety within hospitals, including the implementation of technologies like electronic health records (EHRs), barcode medication administration systems, and artificial intelligence (AI) for early detection of adverse events..</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="nurse.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">NURSING</h5>
            <p class="card-text"> Discuss the importance of placing patients at the center of care delivery and tailoring services to meet their individual needs, preferences, and values. Explore strategies for promoting patient autonomy, dignity, and involvement in decision-making processes..</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer style="background-color: rgb(187, 187, 187);" class="text-center py-3">
    <p>&copy; 2024 susi Pharma SUSINDHAR K M(212223040106)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Products</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body>
  <body style="background-color: rgb(102, 200, 215);"></body>


  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">SUSI PHARMA</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="developments.html">developments</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact_us.html">Contact_us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container py-5">
    <h1 class="text-center mb-4">Our Products</h1>
    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
      <div class="col">
        <div class="card">
          <img src="vitamin.jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">VITAMIN E</h5>
            <p class="card-text">Vitamin E is a group of eight fat soluble compounds that include four tocopherols and four tocotrienols. Vitamin E deficiency, which is rare and usually due to an underlying problem with digesting dietary fat rather than from a diet low in vitamin E, can cause nerve problems.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="syrup.jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">DEXORANGE</h5>
            <p class="card-text"> Dexorange syrup is used for the treatment and prevention of different forms of anaemia due to iron, folic acid and vitamin B12 deficiency. It aids in recovery after surgery or operation. It also improves appetite and reduces weakness and fatigue.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="oinment.jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">POVIDONE</h5>
            <p class="card-text">Povidone iodine topical is used on the skin to treat or prevent skin infection in minor cuts, scrapes, or burns. povidone iodine topical is also used in a medical setting to help prevent infection and promote healing in skin wounds, pressure sores, or surgical incisions</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      </div>
  
  
  </section>

  <footer style="background-color: rgb(108, 108, 108);" class="text-center py-3">
    <p>&copy; 2024 susi Pharma SUSINDHAR K M(212223040106)</p>
  </footer>

</body>
</html>
```
development.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Products</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body>
  <body style="background-color: rgb(102, 200, 215);"></body>


  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">SUSI PHARMA</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="developments.html">developments</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact_us.html">Contact_us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container py-5">
    <h1 class="text-center mb-4">Our Products</h1>
    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
      <div class="col">
        <div class="card">
          <img src="vitamin.jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">VITAMIN E</h5>
            <p class="card-text">Vitamin E is a group of eight fat soluble compounds that include four tocopherols and four tocotrienols. Vitamin E deficiency, which is rare and usually due to an underlying problem with digesting dietary fat rather than from a diet low in vitamin E, can cause nerve problems.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="syrup.jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">DEXORANGE</h5>
            <p class="card-text"> Dexorange syrup is used for the treatment and prevention of different forms of anaemia due to iron, folic acid and vitamin B12 deficiency. It aids in recovery after surgery or operation. It also improves appetite and reduces weakness and fatigue.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="oinment.jpg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">POVIDONE</h5>
            <p class="card-text">Povidone iodine topical is used on the skin to treat or prevent skin infection in minor cuts, scrapes, or burns. povidone iodine topical is also used in a medical setting to help prevent infection and promote healing in skin wounds, pressure sores, or surgical incisions</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      </div>
  
  
  </section>

  <footer style="background-color: rgb(108, 108, 108);" class="text-center py-3">
    <p>&copy; 2024 susi Pharma SUSINDHAR K M(212223040106)</p>
  </footer>

</body>
</html>
```
contact_us.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>contact us</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body>
    <body style="background-color: rgb(38, 64, 106);"></body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">SUSI PHARMA</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="developments.html">DEVELOPMENTS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact_us.html">Contact_us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="container py-5">
    <h1 class="text-center mb-4">Contact Us</h1>
    <div class="row">
      <div class="col-md-6">
        <h3>INFO</h3>
        <p>SUSI PHARMA</p>
        <p>SUSI PHARMA
           chrompet,
           tambaram,
           CHENNAI-600001.
        </p>
        <p>Phone Number: <a href="tel:+987654321">224-228-334-887</a></p>
        <p>Email: <a href="mailto:info@mycompany.com">info@susi.com</a></p>
      </div>
      <div class="col-md-6">
        <h3>To stay in touch </h3>
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">Your Name</label>
            <input type="text" class="form-control" id="name" required>
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email Address</label>
            <input type="email" class="form-control" id="email" required>
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" rows="3" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>
    </div>
  </section>

  <footer style="background-color: rgb(108, 108, 108);" class="text-center py-3">
    <p>&copy; 2024 susi Pharma SUSINDHAR K M(212223040106)</p>
  </footer>
  

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```



## OUTPUT:
![alt text](<steve/Screenshot 2024-05-13 202921.png>)
![alt text](<steve/Screenshot 2024-05-13 202950.png>)
![alt text](<steve/Screenshot 2024-05-13 203005.png>)
![alt text](<steve/Screenshot 2024-05-13 203016.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
