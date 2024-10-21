
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css"
      integrity="sha512-+4zCK9k+qNFUR5X+cKL9EIR+ZOhtIloNl9GIKS57V1MyNsYpYcUrUeQc9vNfzsWfV28IaLL3i96P9sdNyeRssA=="
      crossorigin="anonymous"
    />
    <link rel="stylesheet" href="style.css" />
    <title>Headphones Product Page</title>
  </head>
  <body>
    <nav class="navbar">
      <div class="container">
        <h1 class="logo">SONIC</h1>
        <ul class="nav">
          <li><a href="#home">Home</a></li>
          <li><a href="#categories">Categories</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#contact">Contact</a></li>
          <li><a href="#help">Help</a></li>
        </ul>
      </div>
    </nav>
    <section id="home" class="section-showcase">
      <div class="container">
        <div>
          <h1>The headphones of the future.</h1>
          <p>
            Welcome to our headphones hub, your ultimate destination for all things audio! Explore a curated selection of high-quality headphones, from wireless to noise-canceling models. Whether you're a casual listener or an audiophile, we provide expert reviews, buying guides, and the latest trends to help you find the perfect pair. Experience sound like never before!
          </p>
          <a href="#about" class="btn">Read More</a>
        </div>
        <img src="https://i.ibb.co/37Y74kv/showcase.jpg" alt="" />
      </div>
    </section>
    <section id="about" class="section-large-text">
      <div class="overlay">
        <div class="section-large-text-inner">
          <h3>Loud & Clear</h3>
          <h2>People Aren't Hearing All the Music</h2>
          <p>
            "Unleash the Power of Sound: Discover Your Perfect Headphones for Every Beat, Every Moment!"
          </p>
        </div>
      </div>
    </section>
    <section class="section-gallery">
      <div class="gallery">
        <img src="https://i.ibb.co/CHLBZnp/gal2323.jpg" alt="" class="big" />
        <img src="https://i.ibb.co/4pBbhfY/gal39834.jpg" alt="" class="big" />
        <img src="https://i.ibb.co/xSnHP7g/gal43884.jpg" alt="" class="big" />
        <img src="https://i.ibb.co/QN6Bnrb/gal4958.jpg" alt="" class="big" />
        <img src="https://i.ibb.co/dGZvj75/gal4545.jpg" alt="" class="big" />
        <img src="https://i.ibb.co/S6FVFNt/gal74744.jpg" alt="" class="big" />
      </div>
    </section>
    <footer class="section-footer">
      <div class="container">
        <div>
          <h2>Connect with us on our social media handles</h2>
          <a href="https://instagram.com">
            <i class="fab fa-instagram fa-2x"></i>
          </a>
          <a href="https://facebook.com">
            <i class="fab fa-facebook fa-2x"></i>
          </a>
          <a href="https://youtube.com">
            <i class="fab fa-youtube fa-2x"></i>
          </a>
        </div>
        <div>
          <h3>Company Info</h3>
          <ul>
            <li><a href="#">All Products</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Privacy Policy</a></li>
            <li><a href="#">Terms of Service</a></li>
          </ul>
        </div>
        <div>
          <h3>Blog Posts</h3>
          <ul>
            <li><a href="#">Lorem ipsum dolor.</a></li>
            <li><a href="#">Lorem ipsum dolor.</a></li>
            <li><a href="#">Lorem ipsum dolor.</a></li>
            <li><a href="#">Lorem ipsum dolor.</a></li>
          </ul>
        </div>
        <div>
          <h3>Subscribe</h3>
          <p>subscribe for the latest updates about the products.</p>
          <form name="email-form" onsubmit="event.preventDefault()">
            <div class="email-form">
              <span class="form-control-wrap"
                ><input
                  type="email"
                  name="email"
                  id="email"
                  size="40"
                  class="form-control"
                  placeholder="E-mail" /></span
              ><button type="submit" value="Submit" class="form-control submit">
                <i class="fas fa-chevron-right"></i>
              </button>
            </div>
          </form>
        </div>
      </div>
    </footer>
  </body>
  <style>
    @import url("https://fonts.googleapis.com/css2?family=Catamaran:wght@400;700&display=swap");

:root {
  --primary-color: #0f2b5c;
  --secondary-color: #444;
  --ternary-color: #00ffff;
  --light-color: #ffdfdf;
  --light-secondary-color: #ddd;
  --light-ternary-color: #cb8a8a;
  --overlay-color: rgba(0, 0, 0, 0.7);
}
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: "Catamaran", sans-serif;
  line-height: 1.6;
  color: var(--primary-color);
  font-size: 1.1rem;
}

h1,
h2,
h3,
h4 {
  line-height: 1.3;
}

a {
  color: var(--secondary-color);
  text-decoration: none;
}

ul {
  list-style: none;
}

img {
  width: 100%;
}

.container {
  max-width: 1100px;
  margin: auto;
  overflow: hidden;
  padding: 0 2rem;
}



.navbar {
  font-size: 1.7rem;
  padding: 0.3rem 0;
}

.navbar .container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
}

.navbar ul {
  display: flex;
  justify-self: flex-end;
  align-items: center;
  justify-content: center;
}

.navbar a {
  padding: 0 1rem;
}

.navbar a:hover {
  color: var(--ternary-color);
}



.section-showcase {
  margin: 2rem 0;
}

.section-showcase .container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 3rem;
  align-items: center;
  justify-content: center;
}

.section-showcase h1 {
  font-size: 4rem;
  color: var(--primary-color);
}

.section-showcase p {
  margin: 1rem 0;
}

.btn {
  display: inline-block;
  background-color: var(--primary-color);
  color: #ffffff;
  padding: 0.8rem 1.5rem;
  border: none;
  cursor: pointer;
  font-size: 1.1rem;
  border-radius: 30px;
}

.btn:hover {
  background: var(--secondary-color);
}



.section-large-text {
  position: relative;
  background: url("https://i.ibb.co/1RS1dqC/section-b.jpg") bottom center/cover
    no-repeat;
  height: 600px;
}

.overlay {
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-color: var(--overlay-color);
}

.section-large-text-inner {
  color: #fff;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  margin: auto;
  max-width: 860px;
  padding: 5rem 0;
}

.section-large-text-inner h2 {
  font-size: 5rem;
  margin-top: 1rem;
}

.section-large-text-inner h3 {
  font-size: 2rem;
}

.section-large-text-inner p {
  font-size: 1.5rem;
  margin-top: 1rem;
}



.section-gallery .gallery {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
}

.section-gallery .gallery img:first-child {
  grid-row: 1/3;
  grid-column: 1/3;
}

.section-gallery .gallery img:nth-child(2) {
  grid-column-start: 3;
  grid-column-end: 5;
}

.section-gallery .gallery img {
  width: 100%;
  height: 100%;
}



.section-footer {
  background-color: var(--primary-color);
  color: #fff;
  padding: 4rem 0;
}

.section-footer .container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1rem;
}

.section-footer h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

.section-footer h3 {
  margin-bottom: 0.7rem;
}

.section-footer a {
  line-height: 1.9;
  color: var(--light-color);
}

.section-footer a > i {
  color: var(--ternary-color);
  margin-right: 0.5rem;
}

.email-form {
  display: inline-block;
  width: 100%;
  background-color: var(--ternary-color);
  position: relative;
  border-radius: 20px;
  line-height: 0;
  margin-top: 1rem;
}

.email-form .form-control {
  display: inline-block;
  width: 100%;
  height: 45px;
  border-radius: 20px;
  border: 0;
  outline: 0;
  font-size: 1rem;
  color: var(--light-secondary-color);
  background-color: transparent;
  font-family: inherit;
  margin: 0;
  padding: 0 3rem 0 1.5rem;
}

.email-form .submit {
  display: inline-block;
  position: absolute;
  top: 0;
  right: 0;
  width: 45px;
  height: 45px;
  background-color: var(--light-ternary-color);
  font-size: 1rem;
  text-align: center;
  margin: 0;
  padding: 0;
  outline: 0;
  border: 0;
  border-radius: 0 20px 20px 0;
  color: var(--primary-color);
  cursor: pointer;
}

@media (max-width: 768px) {
  .section-showcase .container {
    grid-template-columns: 1fr;
    text-align: center;
  }

  .section-showcase .container div:first-child {
    order: 2;
  }

  .section-showcase .container div:nth-child(2) {
    order: -1;
  }

  .section-showcase h1 {
    font-size: 2rem;
  }

  .section-showcase img {
    width: 80%;
    margin: auto;
  }

  .section-large-text-inner h2 {
    font-size: 3rem;
  }

  .section-large-text-inner h3 {
    font-size: 1.5rem;
  }

  .section-large-text-inner p {
    font-size: 1.25rem;
  }

  .section-gallery .gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
  }

  .section-gallery .gallery img:first-child {
    grid-row: 1/1;
    grid-column: 1/1;
  }

  .section-gallery .gallery img:nth-child(2) {
    grid-row: 2/2;
    grid-column: 2/4;
  }

  .section-gallery .gallery img:last-child {
    display: none;
  }

  .section-footer {
    padding: 2rem 0;
  }

  .section-footer .container {
    grid-template-columns: 1fr;
    text-align: center;
  }

  .section-footer div:nth-child(2),
  .section-footer div:nth-child(3) {
    display: none;
  }
}
  </style>
</html>
