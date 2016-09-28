# furry-guacamole
layout code for site - test

<!DOCTYPE html>
<html>
<head>
<style>
body {
 background: url("http://www.ediblelongisland.com/wp-content/uploads/sites/3/2014/03/dirty_hands.jpg") no-repeat center center fixed;
 background-size: cover;
   overflow:auto;
   
 <meta name="viewport" content="width=device-width, initial-scale=1">
}
#h1{
font: bold 24px/45px Helvetica, Sans-Serif;
text-decoration: underline;
font-size: 40px;
text-align:center;
font-family: "Times New Roman", Times, serif;
float: left;
}
#h2{
font: bold 24px/45px Helvetica, Sans-Serif;
 font-style: oblique;
font-size: 20px;
text-align:center;
font-family: "Times New Roman", Times, serif;
float: left;
} 
#header
  {
  position:relative;
  width: 100%;
  max-height: 120px;
  margin: 5px 5px 0 5px;
  border: 1px solid black;
  background: rgb(170, 187, 97); /* Fallback */
  background: rgba(170, 187, 97, 0.5);
  text-color: black;
  text-align:center;
 
  float: left;
  font-weight: 200;
  font-size: 18px;
  box-sizing: border-box;
  padding-right: 0px;
 

}

ul {
    list-style-type: none;
    margin: 60px;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

li {
    float: left;
}

li a, .dropbtn {
    display: inline-block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover, .dropdown:hover .dropbtn {
    background-color: red;
}

li.dropdown {
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
	
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}

.dropdown-content a:hover {background-color: #f1f1f1}

.dropdown:hover .dropdown-content {
    display: block;
}

#content
  {
  position: absolute;
  top: 135px;
  height: 555px;
  max-width: 200px;
  max-height: 700px;
  float: none;
  background-color: black;
  border: 1px solid black;
  background: rgb(170, 187, 97); /* Fallback */
  background: rgba(170, 187, 97, 0.5);
  text-align:center;
border-radius: 25px;
  margin-top: 1px;
  margin-bottom: 1px;
  margin-right: 5px;
  margin-left: 5px;
   clear: left;
  padding: 10px;
  width: 10%;
  box-sizing: border-box;
  font-weight: 300;
}

#main
  {
  position: absolute;
  top: 125px;
  left: 207px;
  right:50px;
  height: 550px;
  background-color: green;
  border: 1px solid black;
  background: rgb(170, 187, 97); /* Fallback */
  background: rgba(170, 187, 97, 0.5);
  text-align:center;
  border-radius: 25px;
  overflow: auto;
  clear: bottom;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-around;
  padding: 20px;
  width: 76%;
  box-sizing: border-box;
  font-weight: 300;
  }
  

#main2
  {
  position: relative;
  top: -40px;
  background-color: green;
  border: 1px solid black;
  background: rgb(170, 187, 97); /* Fallback */
  background: rgba(170, 187, 97, 0.5);
  text-align:center;
  border-radius: 25px;
  float:right;
  padding: 0px;
  width: 13%;
  box-sizing: border-box;
  font-weight: 300;
  height: 555px;
  }
  
  #main2 ul  {
    list-style-type: none;-200px
    margin: 0 auto;
    padding: 0;
    background-color: #f1f1f1;
    border: 1px solid #555;
}
#main2 ul li a {
    display: block;
    color: #000;
    padding: 8px 16px;
    text-decoration: none;
}
#main2 ul li {
    text-align: center;
    border-bottom: 1px solid #555;
}
#main2 ul li:last-child {
    border-bottom: none;
}
#main2 ul li a.active {
    background-color: #4CAF50;
    color: white;
}
#main2 ul li a:hover:not(.active) {
    background-color: #555;
    color: white;
}

#footer
  {
  position: absolute;
  top: 700px;
  width: 100%;
  height: 100px;
  border: 1px solid black;
  background: rgb(170, 187, 97); /* Fallback */
  background: rgba(170, 187, 97, 0.5);
  text-align:center;
  border-radius: 25px;
  float:left;
 
}


/* unvisited link */
a:link {
    color: red;
}
/* visited link */
a:visited {
    color: black;
}
/* mouse over link */
a:hover {
    color: white;
}
/* selected link */
a:active {
    color: blue;
}
div.img {
 
    border: 1px solid black;
    float: left;
    width: 200px;
border-radius: 15px 0px 0px 0px;
overflow: hidden;
}
div.img:hover {
    border: 1px solid black;
}
div.img img {
    max-height: 200px;
}

.img {
    max-height: 250px;
}
div.desc {
    padding: 5px;
    text-align: center;
}


</style>
</head>

<body>
  <div id = "header">
 <div id="h1">Gardening in Florida  </div>
<div id= "h2">An inventory about what WILL grow here and tips and information about how to go about it</div>
<ul>
  <li><a class="active" href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li class="dropdown">
    <a href="#" class="dropbtn">Dropdown</a>
    <div class="dropdown-content">
      <a href="#">Link 1</a>
      <a href="#">Link 2</a>
      <a href="#">Link 3</a>
    </div>
  </li>
</ul>

<div id = "footer">jgfkmhyfjkut
</div>

<div id = "main2">tips
<p><b><a href="http://gardeningsolutions.ifas.ufl.edu/plants/trees-and-shrubs/trees/" target="_blank">Gardening by month</a></b></p>

<ul>
  <li><a class="active" href="http://floridagardening.org/seasonal-tips.aspx?monthtip=January">January</a></li>
  <li><a href="http://floridagardening.org/seasonal-tips.aspx?monthtip=February">February</a></li>
  <li><a href="http://floridagardening.org/seasonal-tips.aspx?monthtip=March">March</a></li>
  <li><a
href="http://floridagardening.org/seasonal-tips.aspx?monthtip=April">April</a></li>
  <li><a
href="http://floridagardening.org/seasonal-tips.aspx?monthtip=May">May</a></li>
  <li><a
href="http://floridagardening.org/seasonal-tips.aspx?monthtip=June">June</a></li>
  <li><a
href="http://floridagardening.org/seasonal-tips.aspx?monthtip=July">July</a></li>
  <li><a
href="http://floridagardening.org/seasonal-tips.aspx?monthtip=August">August</a></li>
  <li><a
href="http://floridagardening.org/seasonal-tips.aspx?monthtip=September">September</a></li>
  <li><a
href="http://floridagardening.org/seasonal-tips.aspx?monthtip=October">October</a></li>
  <li><a
href="http://floridagardening.org/seasonal-tips.aspx?monthtip=November">November</a></li>
  <li><a
href="http://floridagardening.org/seasonal-tips.aspx?monthtip=December">December</a></li>

</ul>

</div>

<div id = "content">
<p><b><a href="http://gardeningsolutions.ifas.ufl.edu/plants/trees-and-shrubs/trees/" target="_blank">Trees, Shrubs & Vines</a></b></p>
<p><b><a href="http://gardeningsolutions.ifas.ufl.edu/plants/edibles/vegetables/" target="_blank">Vegetables</a></b></p>
<p><b><a href="http://gardeningsolutions.ifas.ufl.edu/plants/edibles/fruits/" target="_blank">Fruits</a></b></p>
<p><b><a href="http://gardeningsolutions.ifas.ufl.edu/plants/ornamentals/" target="_blank">Flowers & Ornamentals</a></b></p>
<p><b><a href="http://gardeningsolutions.ifas.ufl.edu/design/types-of-gardens/" target="_blank">Types of Gardens</a></b></p>
<p><b><a href="http://gardeningsolutions.ifas.ufl.edu/plants/houseplants/" target="_blank">Houseplants</a></b></p>
<p><b><a href="http://floridagardening.org/gardening-a-to-z.aspx" target="_blank">Gardening A -Z</a></b></p>
<p><b><a href="http://gardeningsolutions.ifas.ufl.edu/care/" target="_blank">General tips for care</a></b></p>
<p><b><a href="http://gardeningsolutions.ifas.ufl.edu/care/pests-and-diseases/pests/" style= "target="_blank">pests</a></b></p>

<a href="http://ifas.ufl.edu/">
  <img src="http://ics.ifas.ufl.edu/images/branding/print-logos/IFAS2013.jpg"
 style="width:100px;height:49px;border:0">
</a>

<a href="http://gardeningsolutions.ifas.ufl.edu/">
  <img src="http://gardeningsolutions.ifas.ufl.edu/clce/images/template/gardening_solutions_footer_logo.png"
 style="width:100px;height:49px;border:0">
</a>


  </div>
 <div id = "main">

<div class="img">
  <a target="_blank" href="http://www.optimara.com/africanvioletcare1.html">
    <img src="http://beautifulviews.net/wp-content/uploads/2013/01/Miniature-African-Violets-We-Used-To-Display-Our-Teacup-Rings.jpg" style=" border-radius: 15px 0px 0px 0px;" "width="300" height="200" >
  </a>
  <div class="desc">African Violets</div>
</div>

<div  class="img">
  <a target="_blank" href="http://gardeningsolutions.ifas.ufl.edu/giam/plants_and_grasses/flowering_plants/amaryllis.html">
    <img src="http://i.ebayimg.com/00/s/ODAwWDgwMA==/z/BfAAAOSwGYVW~zNi/$_35.JPG?set_id=8800005007" style=" border-radius: 15px 0px 0px 0px;""width="300" height="200" >
  </a>
  <div class="desc">Amaryllis</div>
</div>

<div class="img">
  <a target="_blank" href="http://edis.ifas.ufl.edu/mg319">
    <img src="http://blog.davey.com/media/984055/blog_davey_5_myths_annuals_photo_2_.jpg"style=" border-radius: 15px 0px 0px 0px;""width="300" height="200" >
  </a>
  <div class="desc">Annuals</div>
</div>

<div class="img">
  <a target="_blank" href="http://edis.ifas.ufl.edu/MG019">
    <img src="http://fcit.usf.edu/florida/flassets/content/6300/fa6320/fa6320.jpg" style=" border-radius: 15px 0px 0px 0px;""width="300" height="200" >
  </a>
  <div class="desc">Azalea</div>
</div>

<div class="img">
  <a target="_blank" href="http://edis.ifas.ufl.edu/ep337">
    <img src="http://www.lawnchitecture.com/wp-content/uploads/2015/02/BLOG-Bromeliad-many-845x321.jpg" style=" border-radius: 15px 0px 0px 0px;""width="300" height="200" >
  </a>
  <div class="desc">Bromelaids</div>
</div>

<div class="img">
  <a target="_blank" href="https://www.classiccaladiums.com/how_to_plant_caladiums.htm">
    <img src="https://s-media-cache-ak0.pinimg.com/564x/a2/c9/0c/a2c90c56cbbb2ce80e169fd1d3b07fa2.jpg" style=" border-radius: 15px 0px 0px 0px;""width="300" height="200" >
  </a>
  <div class="desc">Caladiums</div>
</div>

<div class="img">
  <a target="_blank" href="http://floridalandscapingtoday.com/camellias-plant/">
    <img src="http://3.bp.blogspot.com/-xm5b5GDE01k/UPdOrz96jDI/AAAAAAAAGR0/aXoVb9FCr9c/s1600/IMG_1333.JPG"style=" border-radius: 15px 0px 0px 0px;""width="300" height="200" >
  </a>
  <div class="desc">Camellias</div>
</div>

<div class="img">
  <a target="_blank" href="http://edis.ifas.ufl.edu/mg216">
    <img src="http://3.bp.blogspot.com/-lp6N0Th7BTs/UZ44-NPXUZI/AAAAAAAAAnU/UPcvyuSVyMI/s1600/Mangifera+indica+-+Mango+Tree+12.jpg" style=" border-radius: 15px 0px 0px 0px;""width="300" height="200" >
  </a>
  <div class="desc">Mangos</div>
</div>

<div class="img">
  <a target="_blank" href="http://www.theweedstreetjournal.com/purple-kush-basic-info-pro-tips/">
    <img src="https://s-media-cache-ak0.pinimg.com/564x/4f/70/93/4f7093f7a4c137676d937b6148da863a.jpg" style=" border-radius: 15px 0px 0px 0px;""width="300" height="200" >
  </a>
  <div class="desc">Rainbow kush</div>
</div>

<div class="img">
  <a target="_blank" href="http://www.south-florida-plant-guide.com/grow-an-orange-tree.html">
    <img src="http://i.waysidegardens.com/images/xxl/36488.jpg"style=" border-radius: 15px 0px 0px 0px;""width="300" height="200" >
  </a>
  <div class="desc">Oranges</div>
</div>

<div class="img">
  <a target="_blank" href="http://gardeningsolutions.ifas.ufl.edu/plants/edibles/fruits/watermelon.html">
    <img src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcS4b0z5eiBD1hsGkG73kKPDyGzCVtS2SGpzHOa2dCNYY4eIfrJp"style=" border-radius: 15px 0px 0px 0px;""width="300" height="200" >
  </a>
  <div class="desc">Watermelon</div>
</div>

<div class="img">
  <a target="_blank" href="http://edis.ifas.ufl.edu/vh021">
    <img src="http://centar-mare.hr/wp-content/uploads/2016/04/vegetables.jpg" 
style=
"border-radius: 15px 0px 0px 0px;" 

"width="300"
 height="200" >
 
 
  </a>
  <div class="desc">Vegetable Gardens</div>
</div>
</div>


</body>
</html>


