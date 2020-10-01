## Writing-in-air-using-finger

## Why do we use HSL instead of HSV?
<p align="center">
    <img src="https://i.stack.imgur.com/v5iIW.png" width="500px"/> 
    <img src="https://docs.opencv.org/master/Threshold_inRange_HSV_colorspace.jpg" width="500px"/>
    
    First image is HSL and Second one is HSV
    
    We use HSl because :
    
    In HSL, the Saturation component always goes from fully saturated color to the equivalent gray (in HSV, with V at
    maximum, it goes from saturated color to white, which may be considered counterintuitive).
    
    The Lightness in HSL always spans the entire range from black through the chosen hue to white (in HSV, the V
    component only goes half that way, from black to the chosen hue). 
</p>

### This is how our project looks like:

<p align="center">
   <video src="https://youtu.be/vzX4cqaTMcY" width="800px">
</p>

### Knowledge required:
<img src="https://cdn.filestackcontent.com/s5AAht0bQv6JnEdKLwkm" width="200px">