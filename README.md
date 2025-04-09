<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      /* General body styles */
      body {
        font-family: Arial, sans-serif;
        text-align: center;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4;
      }

      /* Styling the links and images container */
      figure {
        display: inline-block;
        margin: 20px;
        background-color: #fff;
        border-radius: 10px;
        padding: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      a {
        text-decoration: none;
        color: inherit;
      }

      /* Image styles */
      img {
        width: 100%;
        max-width: 300px;
        height: auto;
        border-radius: 8px;
      }

      /* Add spacing and border to make images look more neat */
      img:hover {
        box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
        transition: box-shadow 0.3s ease-in-out;
      }

      /* Styling captions under each image */
      figcaption {
        margin-top: 8px;
        font-size: 1.1em;
        font-weight: bold;
        color: #333;
      }

      /* Ensure the images scale responsively */
      @media (max-width: 768px) {
        img {
          max-width: 200px;
        }
      }

      @media (max-width: 480px) {
        img {
          max-width: 150px;
        }
      }
    </style>
  </head>
  <body>
    <figure>
      <a href="https://google.com">
        <img
          src="https://logos-world.net/wp-content/uploads/2020/09/Google-Logo.png"
          alt="Google Logo"
        />
        <figcaption>Google</figcaption>
      </a>
    </figure>
    <figure>
      <a href="https://chatgpt.com/">
        <img
          src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTMdM9MEQ0ExL1PmInT3U5I8v63YXBEdoIT0Q&s"
          alt="ChatGPT Logo"
        />
        <figcaption>ChatGPT</figcaption>
      </a>
    </figure>
    <figure>
      <a href="https://www.hotstar.com/in">
        <img
          src="https://www.livemint.com/lm-img/img/2025/02/14/optimize/Screenshot_2025-02-14_065533_1739496378365_1739496389150.png"
          alt="Hotstar Logo"
        />
        <figcaption>Hotstar</figcaption>
      </a>
    </figure>
    <figure>
      <a href="https://www.youtube.com/">
        <img
          src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e1/Logo_of_YouTube_%282015-2017%29.svg/1280px-Logo_of_YouTube_%282015-2017%29.svg.png"
          alt="YouTube Logo"
        />
        <figcaption>YouTube</figcaption>
      </a>
   
  </body>
</html>
