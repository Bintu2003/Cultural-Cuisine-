<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial, Helvetica, sans-serif}
* {box-sizing: border-box;}

.bg-img {
  /* The image used */
  background-image: url("Cultural\ Cuisine-1\ \(3\).jpg");

  min-height: 380px;

  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  
  /* Needed to position the navbar */
  position: relative;
}

/* Position the navbar container inside the image */
.container {
  position: absolute;
  margin: 20px;
  width: auto;
}

/* The navbar */
.topnav {
  overflow: hidden;
  background-color: deeppink;
}

/* Navbar links */
.topnav a {
  float: left;
  color: black:deeppink
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color:black;
  color: pink;
}
</style>
</head>
<body>

<h2>Cultural Cuisine</h2>
<div class="bg-img">
  <div class="container">
    <div class="topnav">
      <a href="index.html">Home</a>
      <a href="booking.html">Booking</a>
        <a href="contact.html">Contact</a>
      <a href="About.html">About</a>
    <a href="Menu.html">Menu</a>
    </div>
  </div>
</div>

</body>
</html>

<!DOCTYPE html>
<html>
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

.header {
  text-align: center;
  padding: 32px;
}

.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
  -ms-flex: 25%; /* IE10 */
  flex: 25%;
  max-width: 25%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    -ms-flex: 50%;
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    -ms-flex: 100%;
    flex: 100%;
    max-width: 100%;
  }
}
</style>
<body>

<!-- Header -->
<div class="header">
  
<img src="5 star.jpg" alt= "5 star">
  
<h1>Our Five Star Award Winning Diversity 
  Restaurant </h1> 
<h1>Since 2016-present</h1>
  <img src="world.jpg" alt="World">

