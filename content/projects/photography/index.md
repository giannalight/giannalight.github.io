+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "Photos"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-05-19T17:02:23-07:00 #the date the file was created
    
    shortDescription = "Photos captured and edited by me"
    projectVideo = ""
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = ""
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "photog.jpg"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = "photo"
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 

+++
</div>

<div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner" >
    <div class="carousel-item active">
      <img src="arc.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="portrait-siler.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="room.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="santc.jpeg" class="d-block w-100" alt="...">
    </div>
     <div class="carousel-item">
      <img src="siportrait.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="wave.jpeg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="lifeg.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="natalia.jpg" class="d-block w-100" alt="...">
    </div>
     <div class="carousel-item">
      <img src="woods.jpeg" class="d-block w-100" alt="...">
    </div>
  <div class="carousel-item">
      <img src="vbeach.jpg" class="d-block w-100" alt="...">
    </div>
<div class="carousel-item">
      <img src="flowers.jpeg" class="d-block w-100" alt="...">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>