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
dribble.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dribbble Style Page (Pure Bootstrap)</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .same-size {
      height: 150px;
      object-fit: cover;
    }
  </style>
</head>
<body class="bg-primary-subtle">

  <nav class="navbar navbar-expand-lg navbar-dark bg-dark px-4">
    <a class="navbar-brand fw-bold text-danger" href="#">Dribbble</a>
    <div class="ms-auto">
      <a href="#" class="text-white fw-semibold me-3 text-decoration-none">Sign in</a>
      <a href="#" class="btn btn-outline-light btn-sm fw-semibold">Sign up</a>
    </div>
  </nav>

  <section class="py-5 text-center">
    <div class="container">
      <div class="text-start">
        <h3 class="text-dark fw-semibold">Shreeshanth R - 25012265</h3>
      </div>
      <h4 class="fw-bold mt-3 text-dark">What are you working on?</h4>
      <p class="text-secondary fw-semibold">Dribbble is show and tell for designers.</p>
      <div class="d-flex justify-content-center gap-3 mt-3">
        <button class="btn btn-outline-dark fw-semibold">Learn more</button>
        <button class="btn btn-primary fw-semibold">Sign up</button>
      </div>
      <div class="border-top border-secondary-subtle mt-5"></div>
    </div>
  </section>

  <div class="container pb-5">
    <div class="row g-4">
      
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="ocean.avif" class="img-fluid rounded same-size" alt="Ocean">
        <p class="fw-bold mt-2">Ocean</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="galaxy.jpg" class="img-fluid rounded same-size" alt="Galaxy">
        <p class="fw-bold mt-2">Galaxy</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="messi4.jpg" class="img-fluid rounded same-size" alt="Messi">
        <p class="fw-bold mt-2">Messi</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="founder.avif" class="img-fluid rounded same-size" alt="Alex Turner">
        <p class="fw-bold mt-2">Alex Turner</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="Arctic Monkeys.jpg" class="img-fluid rounded same-size" alt="Arctic Monkeys">
        <p class="fw-bold mt-2">Arctic Monkeys</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="line without a hook.jpg" class="img-fluid rounded same-size" alt="Line without a hook">
        <p class="fw-bold mt-2">Line without a hook</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="oppenheimer.jpg" class="img-fluid rounded same-size" alt="Oppenheimer">
        <p class="fw-bold mt-2">Oppenheimer</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="winden.jpg" class="img-fluid rounded same-size" alt="Winden Cave">
        <p class="fw-bold mt-2">Winden Cave</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="blackhole.jpg" class="img-fluid rounded same-size" alt="Black hole">
        <p class="fw-bold mt-2">Black hole</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="download.jpeg" class="img-fluid rounded same-size" alt="Hell's Paradise">
        <p class="fw-bold mt-2">Hell's Paradise</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="deadpool.avif" class="img-fluid rounded same-size" alt="Deadpool">
        <p class="fw-bold mt-2">Deadpool</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="albert.jpg" class="img-fluid rounded same-size" alt="Albert Einstein">
        <p class="fw-bold mt-2">Albert Einstein</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="AOT.jpg" class="img-fluid rounded same-size" alt="Attack on Titan">
        <p class="fw-bold mt-2">Attack on Titan</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="GOT.jpg" class="img-fluid rounded same-size" alt="Ghost of Tsushima">
        <p class="fw-bold mt-2">Ghost of Tsushima</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="marvel.avif" class="img-fluid rounded same-size" alt="Captain America">
        <p class="fw-bold mt-2">Captain America</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="porsche.jpg" class="img-fluid rounded same-size" alt="Porsche">
        <p class="fw-bold mt-2">Porsche</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="GOT1.jpg" class="img-fluid rounded same-size" alt="Ghost of Tsushima">
        <p class="fw-bold mt-2">Ghost of Tsushima</p>
      </div>

      <div class="col-6 col-sm-4 col-md-2 text-center">
        <img src="messi5.jpg" class="img-fluid rounded same-size" alt="Goal">
        <p class="fw-bold mt-2">Goal</p>
      </div>
    </div>
  </div>

  <footer class="bg-dark text-white text-center py-3">
    <p class="mb-0">© 2025 Dribbble Style Page by Shreeshanth R</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (59).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
