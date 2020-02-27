<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title>Vick Bit</title>

    <!-- Bootstrap -->
    <!-- Latest compiled and minified CSS -->
    <script src="//code.jquery.com/jquery-latest.min.js"></script>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" crossorigin="anonymous">

    <!-- Optional theme -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap-theme.min.css" integrity="sha384-fLW2N01lMqjakBkx3l/M9EahuwpSfeNvV63J5ezn3uZzapT0u7EYsXMjQV+0En5r" crossorigin="anonymous">

    <!-- Latest compiled and minified JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js" integrity="sha384-0mSbJDEHialfmuBBQP6A4Qrprq5OVfW37PRR3j5ELqxss1yVqOtnepnHVP9aJ7xS" crossorigin="anonymous">
    </script>
    
    

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->

    <style type="text/css">
        #rate:hover{
            border-radius: 5px;
            background-color: white;
            color: black;
        }
        #rate{
            margin-top: 4px;
            padding-top: 5px;
            padding-bottom: 5px;
            text-align: center;
            width:10%;
        }
        #title{
            text-align: center;
        }
        #logo{
            height: 100%;
            width: auto;
        }

        #wrapper{
            margin: 0;
            padding: 0;
            position: relative;
        }
        body{
            margin: 0;
            background-color: black;
        }
        #footer{
            border-top: 1px solid gray;
            width: 100%;
            margin-top: .25%;
        }
        #footer a{
            text-decoration: none;
            color: gray;
        }
        #footer div{
            float: left;
            margin: 0;
            padding: 0 10px;
        }
        #footer p{
            padding: 0;
            margin: 0;
        }
        #content{
            margin: 0 auto;
        }
        .row{
            margin: 0 10px;
        }



        
        #imageContainer{
            margin: 0 auto;
            height: 60%;
            width: 90%;
            text-align: center;
            background-color: black;
            position: relative;
            padding: .25% 0;
            
        }
        #image{
            height: 95%;
        }
        #fileChooser{
            margin: 0 auto;
        }
        #reviewUpload{
            background-color: blue;
            height: 24%;
            position: relative;
            text-align: center;
            margin: 0 auto;
            padding-top: 1%;
            padding-bottom: 0;

        }
        #comment{
            height: 75%;
            width: 70%;
        }
        #submitButton{
            padding: 0;
        }
        #bodyContainer{
            margin: 0;
        }
        #myCarousel img{
            margin: 0 auto;
        }
</style>

</head>
    <body>



        <div></div> 
     
     
        <nav class="navbar navbar-inverse">
            <div class="container-fluid">

              
                <div class="navbar-header">
                    <a href="/">
                        <img class="img-responsive" src="images/vickbit.png" alt="Vick Bit" style="border:0; max-width:44px; float:left;">
                    </a> 

                    <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
                        <span class="sr-only">Toggle navigation</span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>
                  
                </div>
           
           
                <div id="navbar" class="navbar-collapse collapse">
                    
                    <ul class="nav navbar-nav navbar-right">
                        <li class="active">
                            <a href="/">
                                Home
                            </a>
                        </li>
                        <li>
                            <a href="/services/">
                                Services
                            </a>
                        </li>
                        <li>
                            <a href="/blog/">
                                Blog
                            </a>
                        </li>
                        <li>
                            <a href="/contact/">
                                Contact
                            </a>
                        </li>
                    </ul>       
                         
                </div>
           
           
           
           
           
            </div>
        </nav>
       
 
 
 


     








    

    
<!-- Carousel
    ================================================== -->
        <div id="myCarousel" class="carousel slide" data-ride="carousel">
            
            <!-- Indicators -->
            <ol class="carousel-indicators">
                <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                <li data-target="#myCarousel" data-slide-to="1"></li>
            </ol>
            
            
          
            <div class="carousel-inner" role="listbox">

                <div class="item active">
                    <img src="images/front.png" width="80%" align="center">
                    <div class="container">
                        <div class="carousel-caption">
                            <h1></h1>
                  
                        </div>
                    </div>
                </div>

                <div class="item">
                    <img src="images/back.png" width="80%" align="center">
                </div>

    
              
            </div>
          
            <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
                <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
                <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        
        </div><!-- /.carousel -->









  
  
  
       <!-- Special Sections -->
        

        <div class="container">

            <div class="row" align="center">
            
                <div class="col-md-4">
                    <h3>Projects</h3> 
                    <span class="glyphicon glyphicon-wrench" aria-hidden="true"></span>
                  
                    <p>
                        Check out whats being built.
                    </p>
                    <p>
                        <a class="btn btn-primary" href="/projects/">
                            See current work
                        </a>
                    </p>
                </div><!-- /.col-lg-4 -->
                <div class="col-md-4">
                    
                    <h3>Services</h3> 
                    <span class="glyphicon glyphicon-briefcase" aria-hidden="true"></span>
                  
                    <p>
                        See what we have to offer you.
                    </p>
                    <p>
                        <a class="btn btn-primary" href="/services/" role="button">
                            View our services
                        </a>
                    </p>
                </div><!-- /.col-lg-4 -->
                <div class="col-md-4">
                    
                    <h3>Blog</h3> 
                    <span class="glyphicon glyphicon-pencil" aria-hidden="true"></span>
                 
                    <p>
                        See what others have said about our services.
                    </p>
                    <p>
                        <a class="btn btn-primary" href="/blog/" role="button">
                            Check the blog
                        </a>
                    </p>
                </div><!-- /.col-lg-4 -->
            </div><!-- /.row -->

        </div><!-- /.container -->
        
        
        
        
        
        
        <div class="container">
         
         
        
    

    
        <div class="footer">
        <div class="container">
        <!--contact me-->
            <div class="row">
                
                <div class="col-md-12" align="center">
                    <h3>
                        <span class="glyphicon glyphicon-comment" aria-hidden="true"></span> 
                        CONNECT WITH ME
                    </h3>
                    <p><span>Facebook, Twitter, Instagram &amp; more.</span></p>
                    <p>
                        <span class="glyphicon glyphicon-envelope" aria-hidden="true"></span> michael.vickers@vickbit.com
                    </p>
                    <p>
                        <a href="http://facebook.com/vickbit" target="_blank">
                            <img class="img-rounded" src="images/facebook.png" height="32" width="32">
                        </a>
                        <a href="http://instagram.com/_vickbit" target="_blank">
                            <img class="img-rounded" src="images/instagram.png" height="32" width="32">
                        </a>
                    
                        <a href="https://plus.google.com/u/0/101197128123199498238/posts" rel="publisher" target="_top" style="text-decoration:none;">
                            <img src="//ssl.gstatic.com/images/icons/gplus-32.png" alt="Google+" style="border:0;width:32px;height:32px;">
                        </a>               
                    </p>
                </div><!-- /.col-md-12 -->
            </div><!-- /.row -->
            <hr>
            
            <div class="col-md-6" align="left">
                
                <p>
                    © Vick Bit 2016 | <a href="http://vickbit.com">Michael Vickers</a>
                </p>

            </div>
        
            <div class="col-md-6" align="right">
                <ul class="list-inline">
                    <li>
                        <a class="on" href="/">Home</a>
                    </li> |
                    <li>
                        <a href="/services/">Services</a>
                    </li> |
                    <li>
                        <a href="/projects/">Projects</a>
                    </li> |
                    <li>
                        <a href="/blog/">Blog</a>
                    </li> |
                    <li>
                        <a href="/contact/">Contact</a>
                    </li>

                </ul>       
            </div>
        </div>
        <!-- /.container -->
        </div>


  
  


    </body>
</html>
