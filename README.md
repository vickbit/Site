<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title>Syrup Sandwich Studios</title>

    <!-- Bootstrap -->
    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" integrity="sha384-1q8mTJOASx8j1Au+a5WDVnPi2lkFfwwEAa8hDDdjZlpLegxhjVME1fgjWPGmkzs7" crossorigin="anonymous">

    <!-- Optional theme -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap-theme.min.css" integrity="sha384-fLW2N01lMqjakBkx3l/M9EahuwpSfeNvV63J5ezn3uZzapT0u7EYsXMjQV+0En5r" crossorigin="anonymous">

    <!-- Latest compiled and minified JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js" integrity="sha384-0mSbJDEHialfmuBBQP6A4Qrprq5OVfW37PRR3j5ELqxss1yVqOtnepnHVP9aJ7xS" crossorigin="anonymous">
    </script>
    
    <script src="//code.jquery.com/jquery-latest.min.js"></script>
    <link rel="stylesheet" href="unslider-master/dist/css/unslider.css">
    <link rel="stylesheet" href="unslider-master/dist/css/unslider-dots.css">
    <link rel="stylesheet" href="unslider-master/src/css/unslider.less">
    <link rel="stylesheet" href="unslider-master/src/css/unslider-dots.less">
    <link rel="stylesheet" href="unslider-master/src/css/variables.less">
    <script src="unslider-master/src/js/unslider.js"></script>
    <script src="unslider-master/dist/js/unslider-min.js"></script>
    
    

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->


    <style type="text/css">

    #slider{
      background-color: gray;
    }
    img{
      width: 100%;
      height: 500px;
    }
    .unslider-nav ol li{
      width: 20px;
    }

    </style>
  </head>
  <body>
    <nav class="navbar navbar-default">
      <div class="container-fluid">
        <!-- Brand and toggle get grouped for better mobile display -->
        
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">Brand</a>
        </div>

        <!-- Collect the nav links, forms, and other content for toggling -->
        <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
          <ul class="nav navbar-nav">
            <li class="active"><a href="#">Link <span class="sr-only">(current)</span></a></li>
            <li><a href="#">Link</a></li>
            <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
              <ul class="dropdown-menu">
                <li><a href="#">About</a></li>
                <li><a href="#">blog</a></li>
                <li><a href="#">shop</a></li>
                <li role="separator" class="divider"></li>
                <li><a href="#">gallery</a></li>
                <li role="separator" class="divider"></li>
                <li><a href="#">buy</a></li>
              </ul>
            </li>
          </ul>
          <form class="navbar-form navbar-left" role="search">
            <div class="form-group">
              <input type="text" class="form-control" placeholder="Search">
            </div>
            <button type="submit" class="btn btn-default">Submit</button>
          </form>
          <ul class="nav navbar-nav navbar-right">
            <li><a href="#">Link</a></li>
            <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
              <ul class="dropdown-menu">
                <li><a href="#">Action</a></li>
                <li><a href="#">Another action</a></li>
                <li><a href="#">Something else here</a></li>
                <li role="separator" class="divider"></li>
                <li><a href="#">Separated link</a></li>
              </ul>
            </li>
          </ul>
        </div><!-- /.navbar-collapse -->
      </div><!-- /.container-fluid -->
    </nav>
    


    <div id="slider">
    <div class="my-slider">
      <ul>
        <li><img src="images/ogSyrupSignature.jpg" alt="Cats!"></li>
        <li><img src="images/OGSan.jpg" alt="Cats!"></li>
        <li><img src="images/killBill.jpg" alt="Cats!"></li>
        <li><img src="images/ogsyrup.jpg" alt="Cats!"></li>
      </ul>
    </div>
    </div>


    <script>
      $(document).ready(function($) {
        $('.my-slider').unslider({
              autoplay: true,
              infinite: true,
              delay: 5000,
              arrows: false
            }
          );
      });
    </script>
    



    <div class="container" style="min-height:1200px;">
    <div class="row">
        <div class="col-lg-12">
            <h1>Gallery</h1>
            
            <hr>
            
            
            <div class="col-lg-5">
                <h4>Take a Tour</h4>
                <p><div style="border: 0px none; display: block; height: 0px; margin: 0px; padding: 0px; position: static; visibility: hidden; width: auto;" data-source-container-id="" class="wistia_video_foam_dummy"></div><iframe style="width: 445px; height: 278px;" src="//fast.wistia.net/embed/iframe/os96suyypl?videoFoam=true" allowtransparency="true" scrolling="no" class="wistia_embed" name="wistia_embed" allowfullscreen="allowfullscreen" mozallowfullscreen="mozallowfullscreen" webkitallowfullscreen="webkitallowfullscreen" oallowfullscreen="oallowfullscreen" msallowfullscreen="msallowfullscreen" frameborder="0" height="278" width="445"></iframe><script src="//fast.wistia.net/assets/external/E-v1.js"></script></p>
            </div>
            <div class="col-lg-2">
            </div>
            <div class="col-lg-5">
                <h4>Meet the Team</h4>
                <p>
                  <div style="border: 0px none; display: block; height: 0px; margin: 0px; padding: 0px; position: static; visibility: hidden; width: auto;" data-source-container-id="" class="wistia_video_foam_dummy"></div>
                  
                  <iframe style="width: 445px; height: 278px;" src="//fast.wistia.net/embed/iframe/2mh4qdro1k?videoFoam=true" allowtransparency="true" scrolling="no" class="wistia_embed" name="wistia_embed" allowfullscreen="allowfullscreen" mozallowfullscreen="mozallowfullscreen" webkitallowfullscreen="webkitallowfullscreen" oallowfullscreen="oallowfullscreen" msallowfullscreen="msallowfullscreen" frameborder="0" height="278" width="445"></iframe>
                  
                  <script src=""></script>
                </p>
            </div>
            
            <div class="col-lg-12">
                <hr>
            </div>    
            
            <div class="col-xs-12 col-sm-3 col-md-3 col-lg-3">
                <div class="thumbnail">
                    <strong>Name</strong>
                    <div style="display: none;" class="" id=""></div>
                    <a href="" id="">     
                        <img class="" id="" src="" alt=""> 
                    </a>
                    <span class="">
                        <i class="glyphicon glyphicon-heart"></i>
                        &nbsp; 0
                    </span>
                    <span class="">
                        <i class="glyphicon glyphicon-comment"></i>
                        &nbsp; 0
                    </span>
                </div>
            </div>  
            
            
            <div class="col-xs-12 col-sm-3 col-md-3 col-lg-3"> 
              <div class="thumbnail">
                <strong>name</strong>   
                <div style="display: none;" class="" id=""></div> 
                <a href="" id="">     
                  <img class="" id="" src="" alt="">  
                </a>
                <span class="">
                  <i class="glyphicon glyphicon-heart"></i>
                  &nbsp; 0
                </span>
                <span class="">
                  <i class="glyphicon glyphicon-comment"></i>
                  &nbsp; 0
                </span> 
              </div>
            </div>
            
            <div class="col-xs-12 col-sm-3 col-md-3 col-lg-3"> 
              <div class="thumbnail">
                <strong>name</strong>   
                  <div style="display: none;" class="" id="">
                  </div>   
                  <a href="" id="">     
                    <img class="" id="" src="" alt="">   
                  </a>
                  <span class="">
                    <i class="glyphicon glyphicon-heart"></i>
                    &nbsp; 0
                  </span>
                  <span class="">
                    <i class="glyphicon glyphicon-comment"></i>
                    &nbsp; 0
                  </span> 
                </div>
            </div>
        </div>
      </div>
      </div>


    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>
  </body>
</html>
