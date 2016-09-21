<!doctype html>
<head>
<title>Vikhyat Will Win</title>
<link href="css/bootstrap.min.css" rel="stylesheet">
<link href='https://fonts.googleapis.com/css?family=Indie+Flower' rel='stylesheet' type='text/css'>
<style>
 #map {
        background-color:green;
        height: 100%;
      }



body
{
   padding:0px;
   margin-top:0px;
   margin-left:0px;
   //background-image:url("chair.jpg");
}
.box
{
   position:absolute;
   z-index:3;
   //height:100%;
   background-color:transparent;
   width:100%;
}

#menu
{
  height:50px;
  //width:100%;
  background-color:#27363B;
  position:fixed;
  z-index:4;
  //top:100px;
  transition:height 0.3s linear 0s;
}
#image
{ height:660px;
  //width:100%;
 position:fixed;
 z-index:2;
 background-image:url("vikhyat2.jpg");
 background-size:100% 100%;
}

#no1
{
   height:660px;
   background-color:transparent;
   z-index:3;
   width:100%;
   
}
#no2
{
   height:650px;
  background-color:#ff3333;
  //background-color:transparnt;
   //width:100%;
  z-index:3;
   border-top:2px solid brown;
}
#back2
{
   background-color:skyblue;
   background-image:url("tree.jpg");
   background-size:100% 100%;
   height:650px;
   z-index:1;
   position:fixed;
   top:50px;
}
#no3
{
   height:650px;
   background-color:orange;
   //width:100%;
   z-index:3;
}
#no4
{
   height:650px;
   background-color:#ffffff;
    //background-color:transparent;
   //width:100%;
   z-index:3;
}
#no5
{
   height:650px;
   //background-color:pink;
  // background-color:transparent;
  background: #CCC;
opacity: 0.6;
  // width:100%;
   z-index:3;
   
}
#no6
{
   height:615px;
   background-color:blue;
    //background-color:transparent;
   //width:100%;
   z-index:3;
}
#myphoto
{
  background-image:url("me.jpg");
  background-size:100% 100%;
}
#skills
{ height:100%;
  background-image:url("skills3.jpg");
  background-size:100% 100%;
}
</style>
<script>
      function par()
	  {
	     var a=document.getElementById("image");
		 a.style.top=-(window.pageYOffset/4)+"px";
		 
		
	  }
	 
      window.addEventListener("scroll",par,false);
	 
</script>
</head>
<body>
<div class="container-fluid" style="padding:0px;">

      <nav class="navbar-inverse" style="position:fixed; z-index:4; width:100%;">
      
      <div class="container-fluid">
           <div class="navbar-header" >
		       <a href="#" class="nav navbar-brand">Vikhyat Midha Arora</a>
		   </div>
	       
		   
		   <div>
		       <ul class="nav navbar-nav">
			      <li class="active"><a href="#">Home</a></li>
				  <li><a href="#no2">About</a></li>
				  <li ><a href="#no5">Skills</a></li>
				  <li ><a href="#">Projects</a></li>
				  <li ><a href="#">Videos</a></li>
				  <li ><a href="#">Contact us</a></li>
				  
				  
				  
			   </ul>
			   
		   </div>
	  </div>
  </nav>

<div class="col-lg-12" id="image">

</div>

<div class="col-lg-12" style="padding:0px;">
         <div class="col-lg-12" id="no1">
		        
		 
		 
		 </div>
		 <div class="col-lg-12" id="no2">
		          <div class="row">
		                      <div class="col-lg-4"></div>
				              <div class="col-lg-4" style="background-color:transparent; height:100px; margin-top:100px">
				              <h1 style="margin-left:36%; font-family: 'Pacifico', cursive;">About me</h1>
				              </div>
				             <div class="col-lg-4"></div>
		 
		 
		          </div>
		         <div class="row">
		                     <div class="col-lg-2"></div>
				             <div class="col-lg-8" style="background-color:green; height:300px;  ">
							       <div class="row" style="padding:0px; height:100%; ">
								         <div class="col-lg-9" style="background-color:#ffffff; height:100%;">
								           <p style="color:#ff3333; font-size:20px;"> My Name is Vikhyat Midha .Iwas Born in SriGanganagar Rajasthan,I have done my 
										       schooling in NPS.Now I am doing my Bachelors in Computer Science engineering from 
											   JAYPEE university of engineering and technology,guna .Ihave Experience in programming
											   Languages like c,c++ and java.
										   
										   
										   
										   </p>
								         </div>
								        
								         <div class="col-lg-3"  id="myphoto" style="background-color:#00cc99; height:100%;">
								        </div>
							       </div>
							 
							 
							 
							 
							 </div>
				             <div class="col-lg-2"></div>
		          </div>
		</div>
		<figure>
		<div class="col-lg-12" id="back2">
		
		</div>
		<div class="col-lg-12" id="no3">
		              <div class="col-lg-4"></div>
		             <div class="col-lg-4" style="background-color:transparent; height:100px; margin-top:100px">
				              <h1 style="margin-left:36%; font-family: 'Pacifico', cursive;">Skills</h1>
				              </div>
		               <div class="col-lg-4"></div>
		
		
		
		
		</div>
		</figure>
		
		<div class="col-lg-12" id="no4">
		   
		  </div>
		  <div class="col-lg-12" id="no5">
		        <div class="row" style="height:100%;">
			        <div class="col-lg-6" id="skills"></div>
                   <div class="col-lg-6"></div>
                 </div>			   
		  </div>
		  <div class="col-lg-12" id="no6" style="padding:0px;">
		           <div class="row" style="height:100%;">
				       <div class="col-lg-5" id="map"></div>
				      <div class="col-lg-6" style="height:70px; background-color:yellow;"></div>
				    </div>
				
		  </div>
          
          
</div>
</div>
 <script>
        function initMap() {
          var mapDiv = document.getElementById('map');
          var map = new google.maps.Map(mapDiv, {
              center: {lat: 44.540, lng: -78.546},
              zoom: 8
          });
        }
    </script>
    <script async defer
        src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap">
    </script>
	
</body>
</html>
