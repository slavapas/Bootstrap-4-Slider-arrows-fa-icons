replace in the main file which is responsible for slider
<span class="carousel-control-prev-icon" aria-hidden="true"></span> and <span class="carousel-control-next-icon" aria-hidden="true"></span>

with
<i class="fa fa-angle-left" aria-hidden="true"></i> and <i class="fa fa-angle-right" aria-hidden="true"></i>

also add to assets/fonts file 
            fontawesome.woff

in the file functions.php add  
           wp_enqueue_style('font-awesome', '//maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css');
            
