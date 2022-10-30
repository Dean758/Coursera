<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Menu</title>
<style>

/********** Base styles **********/
* {
  box-sizing: border-box;

}
h1 {
  margin-bottom: 15px;
  text-align: center;

}

p {
  border: 3px solid black;
  background-color: blueviolet;
  width: 100%;
  height: 150px;
  color: white;
  padding: 50px.50px.50px.0px;
  font-family: Arial;
  text-align: center;
  
    }
  

 section {
  border: 3px solid black;
  background-color: yellow;
  padding: 5px;
  width: 75%;
  height: 25%;
  position: relative;
  margin-left: auto;
  top: 52px;
  text-align: right;
  }



/* Simple Responsive Framework. */
.container {
  width: 100%;
}

/********** Large devices only **********/
@media (min-width: 992px){
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
    }
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.33%;
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }
}

/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
      }
  .col-md-1 {
    width: 8.3%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
  }
}

</style>
</head>

<body>

<h1>Menu Sampler</h1>

<div class="container">
  <div class="col-lg-4 col-md-6"><section>Campbell's Tuna Noodle Casserole</section><p>This tuna noodle casserole uses condensed cream of mushroom soup to flavor a creamy sauce that is mixed with tuna, egg noodles, and peas, topped with a crunchy bread crumb topping, and baked to perfection.</p></div>

  <div class="col-lg-4 col-md-6"><section>Quick and Easy Pancit</section><p>This quick pancit recipe with chicken, vegetables, and rice noodles is easy and delicious. It will remind you of island fiestas!</p></div>

  <div class="col-lg-4 col-md-12"><section>Deep-Fried Turkey</section><p>Deep-frying makes the turkey crispy on the outside and super juicy on the inside (even the white meat). It also leaves the heat outside! You can deep-fry the turkey in either peanut or vegetable oil, your choice. </p></div>
</div>

</body>
</html>
