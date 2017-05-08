# snow-canvas
> Snowing effect plugin, written by pure JavaScript. [Here is the demo](https://therefor.github.io/snow-canvas/). 

### Usage 
``` 
<script src = "snow.js“></script> 
<script> 
  window.onload = _snowCanvas({ 
      el: element, //the canvas element      
      snowColor: string, //color of snow,default:"#a6a6a6" 
      backgroundColor: string, //background color, default:"black" 
      maxSpeed: number, //max speed of snow, default: 3.5  
      minSpeed: number, //min speed of snow, default: 0.3 
      amount: number, //amount of snow, 150 default 
      rMax: number ,//max radius of snow, default: 4 
      rMin: number, //min  radius of snow, default: 1 
      width: number, // width of canvas, default: window.innerWidth 
      height: number, //height of canvas, default: window.innerHeight 
  });
</script>
``` 

> "el" property must be given, all other properties are alternative. 