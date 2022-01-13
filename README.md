# Bird Flying

CSS3 is powerful enough to let one have amazing effects, such as a 3-D animations.

Doing this demo as a practice of completing the CSS3 advanced skills. <br> 
Especially, enhance a understanding of the using of **border**, **2D trnasforms**, **3D transforms**, and **animations**


## Some important tips in this project:

- Defines the 3-D perspective in parent element (id selector: #sky), such that its descendant elements which are 3D positioned
  to get render in 3D space.
- Specifies position of the entire bird by Flexbox.
- To avoid the bird looks stiff, one can let the bird rotating along Z-axis from 0deg to 360deg.
- The default *transform-origin* is 50% 50% in horizontal and vertical direction. To let the wings flexibly flying up, <br>
  the better solution is to reset the position of the *origin*: 
  <br>
  - left wing should rotate along top right corner(100% 0)   
  - right wing should rotate along top left corner(0 0)
- The wind can be defined individually in 3d space by using *tansform: trnaslate3d(x, y, z)*.

------
![fly Bird](/flyBird_Animation.gif)
