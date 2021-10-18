<?php


/**
 * rectanglesrandomfilled Class
 * This class will output 3 sgv rectangles filled with a random color each one.
 * @author Jean Paul Delaye 
 */
 

class rectanglesrandomfilled  {
	
  public $monocrea="";
  public $cabeza="";
  public $cuerpo="";
  public $piernas="";
	
  public function __construct( ) {
	  
 	   
  }
	
  public function get_mono($parte) {	  
 
	  
		 $monocrea["cabeza"] = array(
           '#0f2649',
           '#1e2870',
       	   '#541c68',
       	   '#9e266b',
           '#ef5b66',
        );
	    $monocrea["cuerpo"] = array(
   	       '#fdb7ba',
           '#f9e2d9',
           '#9ec7bd',
           '#2082a6',
           '#175187',
        );
	    $monocrea["piernas"] = array(
           '#ffb0b0',
           '#ffc3c3',
           '#ffd8d8',
           '#ffbfd0',
           '#ffacc2',
        );
		 return $monocrea[$parte][rand(0, 4)];
	 
  }
	
  function __destruct() { 
     $cabeza =  self::get_mono("cabeza");
	   $cuerpo =  self::get_mono("cuerpo");
	   $piernas =  self::get_mono("piernas");
	   $out="";
     $out.= '<rect width="300" height="300"  style="fill:'.$cabeza.';"     transform="translate(300,300) scale(1) " />' ;
	   $out.= '<rect width="300" height="300"  style="fill:'.$cuerpo.';"     transform="translate(300,600) scale(1) " />' ;
     $out.= '<rect width="300" height="300"  style="fill:'.$piernas.';"     transform="translate(300,900) scale(1) " />' ;

	   echo  '<div id="dibujo"><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 1200 1200">'.$out. "</svg></div>"; 
	  
	  
  }	
}
	
	  $artwork = new rectanglesrandomfilled( );
    
 ?>
