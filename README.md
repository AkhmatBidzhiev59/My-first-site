<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Akhmat Bidzhiev</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
      crossorigin="anonymous" />
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" 
    crossorigin="anonymous"></script>
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png" />
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png" />
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png" />
    <link rel="manifest" href="/site.webmanifest" />
    <style>
     .rounded-img {
        width: 60%;
        border-radius: 50%;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.4);
        padding: 0.6em;
        margin-bottom: 1em
      } 
    </style>
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        <a class="navbar-brand p-0" href="/">
          <img src="AB.png" alt="AB"width="40" />
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="/">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="places.html">Favorite places</a>
            </li>
           
          </ul>
        </div>
      </div>
    </nav>
    <div class="container text-center my-5">
      <div class="row">
      <div class="col-lg-6 col-md-8 mx-auto">
        <img class="rounded-img" src="img.jpg" alt="Akhmat" />
        <h1 class="fw-light">Akhmat Bidzhiev</h1>
        <p class="lead text-muted">
          I am glag to learn software development from this course. In this HTML course
          I shall build my personal website
        </p>
        <a href="https://stashchuk.com" target="_blank" class="btn btn-primary"> 
         
        </a>
        <a href="https://www.youtube.com/CodingTutorials" target="_blank" 
          class="btn btn-secondary">
         
        </a>
      </div>
    </div>
  </body>
</html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My favorite places</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
      crossorigin="anonymous"
    />
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
      crossorigin="anonymous"
    ></script>
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png" />
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png" />
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png" />
    <link rel="manifest" href="/site.webmanifest" />
    <style>
      .card {
        border-radius: 1em;
        text-align: center;
        padding: 1em;
      }
      .card:hover {
        background-color: rgba(0, 0, 0, 0.1);
      }
      .card img {
        border-radius: 50%;
        width: 60%;
        margin: auto;
      }
    </style>
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        <a class="navbar-brand p-0" href="/">
          <img src="AB.png" alt="AB" width="40" />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="/">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="places.html">Favorite places</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <div class="container my-5">
      <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-5">
        <div class="col">
          <div class="card">
            <img
              src="https://picsum.photos/id/1015/300"
              class="card-img-top"
              alt="My image"
            />
            <div class="card-body">
              <h5 class="card-title">River</h5>
              <p class="card-text">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Reiciendis, minima. Maxime dolores et modi quam debitis eum
                recusandae at atque.
              </p>
              <a
                href="https://picsum.photos/id/1015/1500"
                target="_blank"
                class="btn btn-primary"
                >Laarge Photo</a
              >
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <img
              src="https://picsum.photos/id/1018/300"
              class="card-img-top"
              alt="My image"
            />
            <div class="card-body">
              <h5 class="card-title">Mountains</h5>
              <p class="card-text">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sed,
                neque. Eligendi, ad consectetur? Distinctio totam animi dolore.
                Porro, nulla doloremque!
              </p>
              <a
                href="https://picsum.photos/id/1018/1500"
                target="_blank"
                class="btn btn-primary"
                >Laarge Photo</a
              >
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card">
            <img
              src="https://picsum.photos/id/1041/300"
              class="card-img-top"
              alt="My image"
            />
            <div class="card-body">
              <h5 class="card-title">Ocean</h5>
              <p class="card-text">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum
                dignissimos minus, sint quia in delectus? Officia atque dicta
                autem debitis!
              </p>
              <a
                href="https://picsum.photos/id/1041/1500"
                target="_blank"
                class="btn btn-primary"
                >Laarge Photo</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>

