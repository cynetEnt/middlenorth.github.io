<html>
    <head>
        <title>Middle North Coop Ltd</title>
        <link rel="stylesheet" href="style.css"> 
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css"> 
    </head>
    
    <body>
         
        <div class="menu-bar">
            <div class="logo"> <p>Middle North Cooperative Union Limitted</p></div>
            <div class="content">
                <h1>Creating Web page &<br><span>Developing web page</span><br></h1>
                <button class="cn"><a href="#">Join Us</a></button>
                       </div>
                       <div class="contact"><h2>Contact: +256780222557</h2></div>
                       <div class="email"><h2>Email: tumwesigyeerick@gmail.com</h2></div>  
       <ul>
           <li class="active"><a href="#"><i class="fa fa-home"></i><a href="Home/HTML practicals.html">Home</a></a></li>
           <li><a href="#"><i class="fa fa-user"></i>About us</a>
        <div class="sub-menu-1">
<ul>
<li><a href="#">Mission</a></li>
<li><a href="#">Vision</a></li>
<li><a href="#">Team</a></li>
</ul>
        </div>
        </li>

           <li><a href="#"><i class="fa fa-clone"></i>Services</a>
            <div class="sub-menu-1">
                <ul>
                <li><a href="#">Loan</a></li>
                <li class="hover-me"><a href="#">Agric Extension Services</a><i class="fa fa-angle-right"></i>
                <div class="sub-menu-2"> 
                    <ul>
                        <li><a href="#">Mechanization</a></li>
                        <li><a href="#">crop husbandary</a></li>
                        <li><a href="#"><a href="Home/patosite.html">Livestocks</a></a></li>
                        </ul>

                </div>
                </li>
                <li class="hover-me"><a href="#">Inputs</a><i class="fa fa-angle-right"></i>
                    <div class="sub-menu-2"> 
                        <ul>
                            <li><a href="#">Seeds</a></li>
                            <li><a href="#">farm power</a></li>
                            <li><a href="#">Fertilizers</a></li>
                            </ul>
    
                    </div>
                </li>
                </ul>
                        </div>
        </li>
           <li><a href="#"><i class="fa fa-users"></i>AGM</a>
            <div class="sub-menu-1">
                <ul>
                <li><a href="#">Report 2021</a></li>
                <li><a href="#">Report 20219</a></li>
                <li><a href="#">Report 2018</a></li>
                </ul>
                        </div>
        </li>
           <li><a href="#"><i class="fa fa-angellist"></i>Activities</a>
            <div class="sub-menu-1">
                <ul>
                <li><a href="#">Training Farmers</a></li>
                <li><a href="#">Marketing farmer's produce</a></li>
                <li><a href="#">Provide storage Facilities</a></li>
                </ul>
                        </div>
        </li>
           <li><a href="#"><i class="fa fa-inr"></i>Products</a>
            <div class="sub-menu-1">
                <ul>
                <li><a href="#">Maize Flour</a></li>
                <li><a href="#">Grains</a></li>
                <li><a href="#">Team</a></li>
                </ul>
                        </div>
        </li>
           <li><a href="#"><i class="fa fa-phone"></i>Contacts</a>
            <div class="sub-menu-1">
                <ul>
                <li><a href="#">Tell: +256780222557</a></li>
                <li><a href="#">Email: tumwesigyeerick@gmail.com</a></li>
                <li><a href="#">Team</a></li>
                </ul>
                        </div>
        </li>
        <div class="search">
            <input class="srch" type="search" name="" placeholder="type to text">
            <a href="#"> <button class="btn">search</button></a>
                   </div> 
       </ul>
       
    </div>
       
       </body>
</html>
*
{padding: 0;
margin: 0;
box-sizing: border-box;
}
body
{
    background-image: url(cover.JPG);
    background-size: cover;
    background-position: center;
    font-family: sans-serif;
    background-repeat: no-repeat;
}
.menu-bar
{
background: rgb(0,100,0) transparent;
text-align: center;
height: 120px;
}
.menu-bar ul
{
display: inline-flex;
list-style: none;
color: white;
margin-top: 55px;
}
.menu-bar ul li
{
    width: 120px;
    margin: 15px;
    padding: 15px;
}
.menu-bar ul li a
{
text-decoration: none;
color: orange;
font-weight: bold;
}
.active, .menu-bar ul li:hover
{
    background:  rgb(0,100,0);
    border-radius: 10px;
} 
  menu-bar .fa
  {
      margin-right: 8px;
  }
  .sub-menu-1
  {
      display: none;
  }
  .menu-bar ul li:hover .sub-menu-1
  {
      display: block;
      position: absolute;
      background: #2bab0d;
      margin-top: 15px;
      margin-left: -15px;
      margin-block: 10px;

  }
  .menu-bar ul li:hover .sub-menu-1 ul
  {
      display: block;
      margin: 10px;
      
  }
  .menu-bar ul li:hover .sub-menu-1 ul li
  {
      width: 150px;
      padding: 10px;
      border-bottom: 1px dotted #fff;
      background: transparent;
      border-radius: 0;
      text-align: left;
  }
  .menu-bar ul li:hover .sub-menu-1 ul li:last-child
  {
      border-bottom: none;
  }
  .menu-bar ul li:hover .sub-menu-1 ul li a:hover
  {
      color: #b2ff00;
  }
  .fa fa-angle-right
  {
      float: right;
  }
.sub-menu-2
{
    display: none;
}
.hover-me:hover .sub-menu-2
{
    position: absolute;
    display: block;
    margin-top: -40px;
    margin-left: 14px;
    background: rgb(0,100,0);
}
.search{
    width: 330px;
    float: left;
    margin-left: -30px;
    margin-top: -65px;
}

.srch{
    font-family: 'Times New Roman';
    width: 230px;
    height: 40px;
    background: transparent;
    border: 1px solid orange;
    margin-top: 35px;
    color: #fff;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}

.btn{
    width: 100px;
    height: 40px;
    background: #ff7200;
    border: 2px solid #ff7200;
    margin-top: 35px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5;
    border-bottom-right-radius: 5;
}
.btn:focus{
    outline: none;

}
.srch:focus{
    outline: none;
}
.content{
    width: 350px;
    height: auto;
    margin-top: 200px;
    color: #fff;
    position: absolute;
}
.content:par{
    padding: 20px;
    padding-bottom: 25px;
    font-family: Arial;
    letter-spacing: 1.2px;
    line-height: 30px;
}
.logo{
    width: 550px;
    font-family: 'Times New Roman';
    font-size: 30px;
    color:rgb(0,100,0);
    position: absolute;
margin-top: 15px;
}

.contact{
    width: 1550px;
    position: absolute;
    font-size: 10px;
    margin-top: 10px;
    color: blue;
    font-family: 'Times New Roman';
}

.email{
    width: 1625px;
    position: absolute;
    font-size: 10px;
    margin-top: 40px;
    color: blue;
    font-family: 'Times New Roman';
}
