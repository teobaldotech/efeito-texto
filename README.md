<html>
  <head>
    <title>  t e x t o </title>
    <link rel="stylesheet" type="text/css" href="css/estilo.css">
    <!--[if IE]>
    <link rel="stylesheet" type="text/css" href="css/estiloie.css">
    <![endif]-->

  </head>
  

  



  
    <body>
        
      <span>c</span><span>o</span><span>l</span><span>o</span><span>r</span><picture> 
        <source media="(min-width: )" srcset="">
        <img src="" alt="">
      </picture></span><span>&nbsp;</span><span>e</span><span>f</span><span>f</span><span>e</span><span>c</span><span>t</span>t&nbsp;</span><span>T</span><span>e</span><span>x</span><span>t</span><span>&nbsp;</span>
        
  
    
     <style>

     @import "compass/css3";

@import url(https://fonts.googleapis.com/css?family=Finger+Paint);

body {
  background: black;
  overflow: hidden;
  font: 5vw/100vh "Finger Paint";
  text-align: center;
  color: transparent;
  backface-visibility: hidden;
}

span {
  display: inline-block;
  text-shadow: 0 0 0 whitesmoke;
  animation: smoky 5s 3s both;
}

span:nth-child(even){
  animation-name: smoky-mirror;
}

@keyframes smoky {
  60% {
    text-shadow: 0 0 40px whitesmoke;
  }
  to {
    transform:
      translate3d(15rem,-8rem,0)
      rotate(-40deg)
      skewX(70deg)
      scale(1.5);
    text-shadow: 0 0 20px whitesmoke;
    opacity: 0;
  }
}

@keyframes smoky-mirror {
  60% {
    text-shadow: 0 0 40px whitesmoke; }
  to {
    transform:
      translate3d(18rem,-8rem,0)
      rotate(-40deg) 
      skewX(-70deg)
      scale(2);
     text-shadow: 0 0 20px whitesmoke;
    opacity: 0;
  }
}

@for $item from 1 through 21 {
  span:nth-of-type(#{$item}){ 
    animation-delay: #{(3 + ($item/10))}s; 
  }
} 

  

