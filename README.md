<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Harry Potter and the Goblet of Fire</title>
<style>
@font-face {
    font-family: 'Lumos';
    src: url('fonts/lumos.woff2') format('woff2'), url('fonts/lumos.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
body {
    font-family: 'Lumos', sans-serif;
    margin: 0;
    padding: 0;
    color: #e0e0e0;
    cursor: url("Magic-wand.png") 4 4, auto;
    background: rgba(10, 10, 10, 0.85); /* Fondo oscuro translúcido */
}
#background-video {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: contain;
    z-index: -1;
    opacity: 0.5;
}
.wrapper {
    width: 1366px;
    margin: 0 auto;
    overflow: hidden;
    padding: 20px;
}
header {
    background-color: rgba(51, 51, 51, 0.8);
    padding: 20px;
    text-align: center;
    border-radius: 10px;
}
nav {
    background-color: rgba(68, 68, 68, 0.8);
    padding: 10px 0;
    text-align: center;
    margin-top: 10px;
    border-radius: 10px;
}
nav a {
    color: #f0f0f0;
    text-decoration: none;
    padding: 10px 20px;
    margin: 0 10px;
    border-radius: 5px;
}
nav a:hover {
    background-color: #555;
    cursor: url("Magic-wand.png") 4 4, auto;
}
main {
    margin-top: 20px;
}
.banner img {
    display: block;
    margin: 0 auto;
    width: 50%;
    height: auto;
    box-shadow: 0 0 25px rgba(0, 0, 0, 0.8);
}
.promo-text, .cast-crew, .trailer {
    background-color: rgba(34, 34, 34, 0.85);
    border-radius: 8px;
    padding: 20px;
    margin: 30px auto;
    width: 90%;
}
.promo-text h2, .cast-crew h2, .trailer h2 {
    margin-top: 0;
}
.trailer video {
    display: block;
    margin: 20px auto 0 auto;
    max-width: 100%;
    height: auto;
    border-radius: 10px;
}
footer {
    background-color: rgba(51, 51, 51, 0.8);
    color: #777;
    text-align: center;
    padding: 10px 0;
    margin-top: 30px;
    font-size: 0.8em;
    border-radius: 10px;
}

@media (max-width: 768px) {
.wrapper {
    width: 95%;
    padding: 10px;
}
nav a {
    display: block;
    margin: 10px 0;
}
.banner img {
    width: 90%;
}
video {
    width: 100%;
    height: auto;
}
}
</style>
</head>

<body>
<video autoplay muted loop id="background-video">
  <source src="vecteezy_ai-generative-scary-haunted-mansion_34334820.MOV" type="video/mp4">
  Your browser does not support the video tag. </video>
<div class="wrapper">
  <header>
    <h1>Harry Potter and the Goblet of Fire</h1>
  </header>
  <nav> <a href="index.html">Home</a> <a href="cast.html">Cast</a> <a href="trailer.html">Trailer</a> <a href="gallery.html">Gallery</a> <a href="synopsis.html">Synopsis</a> </nav>
  <main>
    <section class="banner"> <img src="Harry-Potter-Banner.png" alt="Harry Potter and the Goblet of Fire Poster"> </section>
    <section class="promo-text">
      <h2>A New and Dangerous Adventure Awaits</h2>
      <p>In Harry's fourth year at Hogwarts, the mysterious Triwizard Tournament is held, and against all odds, Harry is chosen as one of the champions. Facing dangerous tasks, dragons, and the growing threat of Lord Voldemort, Harry must find the courage and the help of his friends to survive this deadly challenge.</p>
    </section>
    <section class="cast-crew">
      <h2>Main Cast</h2>
      <ul>
        <li>Daniel Radcliffe as Harry Potter</li>
        <li>Rupert Grint as Ron Weasley</li>
        <li>Emma Watson as Hermione Granger</li>
      </ul>
      <h2>Director</h2>
      <p>Mike Newell</p>
    </section>
    <section class="trailer">
      <h2>Trailer</h2>
      <video controls>
        <source src="Harry-Potter-4.mov" type="video/mp4">
        Your browser does not support the video tag. </video>
    </section>
  </main>
  <footer>
    <p>© 2025, Rosana Hourquebie. This is a fictitious web page created solely for the purpose of education and training. All products and people associated with this web page are also fictitious. Any resemblance to real brands, products, or people is purely coincidental. Information provided about the product is also fictitious and should not be construed to be representative of actual products on the market in a similar product category.</p>
  </footer>
</div>
</body>
</html>
