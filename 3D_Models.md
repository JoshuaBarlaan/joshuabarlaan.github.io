# 3D Models

<body>

<h2 style="text-align:center">Slideshow Gallery</h2>

<div class="container">
  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <model-viewer src="tube/tube_glb_files/tube_bottom.glb"
              alt="A 3D model of a tube"
              auto-rotate
              camera-controls></model-viewer>
  </div>

  <div class="mySlides">
    <div class="numbertext">2 / 6</div>
    <img src="img_5terre_wide.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 6</div>
    <img src="img_mountains_wide.jpg" style="width:100%">
  </div>
    
  <div class="mySlides">
    <div class="numbertext">4 / 6</div>
    <img src="img_lights_wide.jpg" style="width:100%">
  </div>

  <div class="mySlides">
    <div class="numbertext">5 / 6</div>
    <img src="img_nature_wide.jpg" style="width:100%">
  </div>
    
  <div class="mySlides">
    <div class="numbertext">6 / 6</div>
    <img src="img_snow_wide.jpg" style="width:100%">
  </div>
    
  <a class="prev" onclick="plusSlides(-1)">❮</a>
  <a class="next" onclick="plusSlides(1)">❯</a>

  <div class="caption-container">
    <p id="caption"></p>
  </div>

  <div class="row">
    <div class="column">
      <img class="demo cursor" src="img_woods.jpg" style="width:100%" onclick="currentSlide(1)" alt="The Woods">
    </div>
    <div class="column">
      <img class="demo cursor" src="img_5terre.jpg" style="width:100%" onclick="currentSlide(2)" alt="Cinque Terre">
    </div>
    <div class="column">
      <img class="demo cursor" src="img_mountains.jpg" style="width:100%" onclick="currentSlide(3)" alt="Mountains and fjords">
    </div>
    <div class="column">
      <img class="demo cursor" src="img_lights.jpg" style="width:100%" onclick="currentSlide(4)" alt="Northern Lights">
    </div>
    <div class="column">
      <img class="demo cursor" src="img_nature.jpg" style="width:100%" onclick="currentSlide(5)" alt="Nature and sunrise">
    </div>    
    <div class="column">
      <img class="demo cursor" src="img_snow.jpg" style="width:100%" onclick="currentSlide(6)" alt="Snowy Mountains">
    </div>
  </div>
</div>

## Tube

### Assembled Model
<model-viewer src="tube/tube_glb_files/tube.glb"
              alt="A 3D model of a tube"
              auto-rotate
              camera-controls></model-viewer>

### Model Part 1 - Bottom

<model-viewer src="tube/tube_glb_files/tube_bottom.glb"
              alt="A 3D model of a tube"
              auto-rotate
              camera-controls></model-viewer>

### Model Part 2 - Middle

<model-viewer src="tube/tube_glb_files/tube_middle.glb"
              alt="A 3D model of a tube"
              auto-rotate
              camera-controls></model-viewer>

### Model Part 3 - Cap

<model-viewer src="tube/tube_glb_files/tube_cap.glb"
              alt="A 3D model of a tube"
              auto-rotate
              camera-controls></model-viewer>

### Assembly Instructions and notes
- Print at least 1 copy of bottom, and cap.  
- This will create a tube of internal length of about 135mm  
- by adding the Middle part to the tube will add about 125mm to this length. 
- You are able to add as many Middle parts though the stability will be in question. 
- The example model has 2 copies of the middle part.  
- The design has friction fit in mind. But gluing the parts together is recommended.  
- Use of any Adhesive such as super glue. 
- For my use case, Hot-melt Adhesive/hot glue is enough.  
- the model having multiple parts allows the user to customize where the model opens.  
	- such as having it open at the top by ungluing the cap or somewhere in the middle.  
