# bootstrap-4.0-carousel-only

Carousel extract from Bootstrap 4: https://getbootstrap.com/

# Initialization

- Call carousel.css and carousel.min.js files in the `<head></head>` of your HTML file,
- Call JQuery with a CDN or by downloading here: http://code.jquery.com/ (JQuery Core part)
- Don't forger to change `PATH` by yours (ex: `/static/bootstrap-4.0/carousel.css`)

# How to use

It's just a part of Bootstrap 4 Framework, use it with the official documentation: https://getbootstrap.com/docs/4.0/components/carousel/

# Example

```html
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="PATH/bootstrap-4.0/carousel.css">
    <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script type="text/javascript" src="PATH/bootstrap-4.0/carousel.min.js"></script>
  </head>
  <body>
    <div id="carouselExampleSlidesOnly" class="carousel slide" data-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img class="d-block w-100" src="..." alt="First slide">
        </div>
        <div class="carousel-item">
          <img class="d-block w-100" src="..." alt="Second slide">
        </div>
        <div class="carousel-item">
          <img class="d-block w-100" src="..." alt="Third slide">
        </div>
      </div>
    </div>
  </body>
</html>
```
