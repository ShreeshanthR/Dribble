# Project Responsive Web Design using Bootstrap
## Date:14.10.2025

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
  <title>Dribbble Style Page (Bootstrap Only, Final)</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body style="background-color: rgb(46, 114, 174); min-height: 100vh; margin: 0;">

  <!-- Black top bar -->
  <nav class="navbar navbar-dark bg-dark px-3">
    <span class="navbar-brand mb-0 h1 text-primary fw-bold">Dribbble</span>
    <div class="d-flex align-items-center">
      <a href="#" class="text-white text-decoration-none fw-bold me-3">Sign in</a>
      <a href="#" class="btn btn-primary btn-sm fw-semibold">Sign up</a>
    </div>
  </nav>

  <!-- Header section -->
  <div class="text-center py-4">
    <div class="container">
      <h3 class="text-start text-white">Shreeshanth R - 25012265</h3>
      <h4 class="fw-bold text-white">What are you working on?</h4>
      <p class="mb-3 text-light">Dribbble is show and tell for designers.</p>
      <div>
        <button class="btn btn-secondary me-2">Learn more</button>
        <button class="btn btn-primary">Sign up</button>
      </div>
      <hr class="mt-4 border-white">
    </div>
  </div>

  <!-- Image grid -->
  <div class="container pb-4">
    <div class="row g-3">
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="ocean.avif" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Ocean</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="galaxy.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Galaxy</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="messi4.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Messi</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="founder.avif" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Alex Turner</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="Arctic Monkeys.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Arctic Monkeys</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="line without a hook.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Line without a hook</div>
      </div>
    </div>

    <div class="row g-3 mt-3">
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="oppenheimer.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Oppenheimer</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="winden.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Winden cave</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="blackhole.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Black hole</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="download.jpeg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Hell's Paradise</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="deadpool.avif" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Deadpool</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="albert.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Albert Einstein</div>
      </div>
    </div>

    <div class="row g-3 mt-3">
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="AOT.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Attack on titan</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="GOT.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Ghost of Tsushima</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="marvel.avif" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Captain America</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="porsche.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Porsche</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="GOT1.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Ghost of Tsushima</div>
      </div>
      <div class="col-6 col-sm-4 col-md-2 text-center">
        <div class="ratio ratio-1x1">
          <img src="messi5.jpg" class="w-100 h-100 object-fit-cover rounded" alt="">
        </div>
        <div class="fw-bold mt-2 text-white">Goal</div>
      </div>
    </div>
  </div>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot (77).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
