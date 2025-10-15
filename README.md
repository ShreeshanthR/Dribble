# Project Responsive Web Design using Bootstrap
## Date:12.10.0205

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
  <title>Dribbble Style Page</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background-color: rgb(46, 114, 174);
    }
    .dribbble-bar {
      background-color: black;
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .dribbble-logo {
      color: rgb(0, 106, 255);
      font-size: 24px;
      font-weight: bold;
    }
    .auth-links a {
      color: white;
      text-decoration: none;
      margin-right: 15px;
      font-weight: bold;
    }
    .btn-signup-sm {
      background-color: rgb(4, 0, 255);
      color: white;
      padding: 5px 10px;
      font-size: 14px;
      border: none;
      border-radius: 4px;
      text-decoration: none;
    }
    .secondary-bar {
      background-color: white;
      padding: 15px 20px;
      font-weight: bold;
      font-size: 16px;
    }
    .grey-header {
      background-color: rgb(46, 114, 174);
      padding: 30px 20px;
      text-align: center; 
    }
    .subtext {
      color: rgb(0, 0, 0);
    }
    .btn-learn {
      background-color: grey;
      color: white;
    }
    .btn-signup {
      background-color: rgb(0, 26, 255);
      color: white;
    }
    .image-label {
      font-size: 14px;
      text-align: center;
      margin-top: 5px;
      font-weight: bold;
    }
    img.same-size {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }
    hr {
      border-top: 1px solid white;
    }
  </style>
</head>
<body>

  <div class="dribbble-bar">
    <span class="dribbble-logo">Dribbble</span>
    <div class="auth-links">
      <a href="#">Sign in</a>
      <a href="#" class="btn-signup-sm">Sign up</a>
    </div>
  </div>
  <div class="grey-header">
    <h3 align="left">Shreeshanth R - 25012265</h3>
    <h4 class="fw-bold">What are you working on?</h4>
    <p class="subtext">Dribbble is show and tell for designers.</p>
    <button class="btn btn-learn me-2">Learn more</button>
    <button class="btn btn-signup">Sign up</button>
    <hr class="mt-4">
  </div>
  <div class="container">
    <div class="row mb-4">
      <div class="col-2 text-center">
        <img src="ocean.avif" class="img-fluid rounded same-size">
        <div class="image-label">Ocean</div>
      </div>
      <div class="col-2 text-center">
        <img src="galaxy.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Galaxy</div>
      </div>
      <div class="col-2 text-center">
        <img src="messi4.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Messi</div>
      </div>
      <div class="col-2 text-center">
        <img src="founder.avif" class="img-fluid rounded same-size">
        <div class="image-label">Alex Turner</div>
      </div>
      <div class="col-2 text-center">
        <img src="Arctic Monkeys.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Arctic Monkeys</div>
      </div>
      <div class="col-2 text-center">
        <img src="line without a hook.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Line without a hook</div>
      </div>
    </div>
    <div class="row mb-4">
      <div class="col-2 text-center">
        <img src="oppenheimer.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Oppenheimer</div>
      </div>
      <div class="col-2 text-center">
        <img src="winden.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Winden cave</div>
      </div>
      <div class="col-2 text-center">
        <img src="blackhole.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Black hole</div>
      </div>
      <div class="col-2 text-center">
        <img src="download.jpeg" class="img-fluid rounded same-size">
        <div class="image-label">Hell's Paradise</div>
      </div>
      <div class="col-2 text-center">
        <img src="deadpool.avif" class="img-fluid rounded same-size">
        <div class="image-label">Deadpool</div>
      </div>
      <div class="col-2 text-center">
        <img src="albert.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Albert Einstein</div>
      </div>
    </div>
    <div class="row mb-4">
      <div class="col-2 text-center">
        <img src="AOT.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Attack on titan</div>
      </div>
      <div class="col-2 text-center">
        <img src="GOT.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Ghost of Tsushima</div>
      </div>
      <div class="col-2 text-center">
        <img src="marvel.avif" class="img-fluid rounded same-size">
        <div class="image-label">Captain America</div>
      </div>
      <div class="col-2 text-center">
        <img src="porsche.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Porsche</div>
      </div>
      <div class="col-2 text-center">
        <img src="GOT1.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Ghost of Tsushima</div>
      </div>
      <div class="col-2 text-center">
        <img src="messi5.jpg" class="img-fluid rounded same-size">
        <div class="image-label">Goal</div>
      </div>
    </div>
  </div>

</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (48).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
