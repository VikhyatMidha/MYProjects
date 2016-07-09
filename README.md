<!doctype html>
<head>
<link href="css/bootstrap.min.css" rel="stylesheet">
<style>
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
  width:100%;
  background-color:#27363B;
  position:fixed;
  z-index:4;
  //top:100px;
  transition:height 0.3s linear 0s;
}
#image
{ height:660px;
  width:100%;
 position:fixed;
 background-image:url("vikhyat2.jpg");
 background-size:100% 100%;
}

#no1
{
   height:660px;
   background-color:transparent;
   
   width:100%;
}
#no2
{
   height:650px;
  background-color:#ffffff;
  //background-color:transparnt;
   width:100%;
  
   border-top:2px solid brown;
}
#no3
{
   height:650px;
   background-color:orange;
   width:100%;
}
#no4
{
   height:650px;
   background-color:grey;
   width:100%;
   
}
#no5
{
   height:650px;
   background-color:pink;
   width:100%;
   
}
#no6
{
   height:650px;
   background-color:blue;
   width:100%;
   
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
				  <li><a href="#">About</a></li>
				  <li ><a href="#">Skills</a></li>
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
				              <div class="col-lg-4" style="background-color:transparent; height:100px;">
				              <h1 style="margin-left:36%;">About</h1>
				              </div>
				             <div class="col-lg-4"></div>
		 
		 
		          </div>
		         <div class="row">
		                     <div class="col-lg-2"></div>
				             <div class="col-lg-8" style="background-color:green; height:300px;"></div>
				             <div class="col-lg-2"></div>
		          </div>
		</div>
		<div class="col-lg-12" id="no3">
		         
		
		
		
		
		
		</div>
		<div class="col-lg-12" id="no4">
		   
		  </div>
		  <div class="col-lg-12" id="no5">
		   
		  </div>
		  <div class="col-lg-12" id="no6">
		   
		  </div>
          
          
</div>
</div>
</body>
</html>
