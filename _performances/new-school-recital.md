---
layout: post
title: New School Degree Recital
category: "New School"
year: 2024
date: 2024-04-19
permalink: /_performances/new-school-recital/
---
<style>
body {
  color: white;
  font-family: monospace;
  font-size: 18px;
  line-height: 1.4;
  margin: 0;
  min-height: 100%;
  overflow-wrap: break-word;
   text-shadow: 
  0 0 0 black,
  1px 0 0 black,
  -1px 0 0 black,
  0 1px 0 black,
  0 -1px 0 black,
  1px 1px 0 black,
  -1px -1px 0 black,
  1px -1px 0 black,
  -1px 1px 0 black,
  2px 0 0 black,
  -2px 0 0 black,
  0 2px 0 black,
  0 -2px 0 black;
}

body {
    background-image: url('/assets/playing.jpeg'); 
    background-size: cover; 
    background-position: center; 
    background-attachment: fixed; 
}

a {
    color:rgb(255, 255, 255); /* This changes the link color */
    
}

/* body, a {
  text-shadow: 
    2px 2px 4px rgba(0,0,0,1),   
    -2px -2px 4px rgba(0,0,0,1),  
    0px 0px 8px rgba(0,0,0,1);    
}
*/

</style>

<iframe width="700" height="394"
    src="https://www.youtube.com/embed/3oJnpU6dzO4?si=bEhax4o-06yTcjZ6"
    frameborder="0"
    allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
</iframe>



# My BFA senior recital

*Date*: April 19th 2024, 6pm

*Location*: College of Performing Arts at The New School, 5th floor Performance Space 55 W 13th St, New York, NY 10011

# *Poster, Program and Stage Plot*

<div class="image-row">
  <img src="{{ site.url }}/assets/TimothyMassorecitalpostercopy.png" alt="Poster">
  <img src="{{ site.url }}/assets/program.png" alt="Program">
</div>

<div class="image-stageplot">
  <img src="{{ site.url }}/assets/TimothyMassoStagePlot.png" alt="Stage Plot">
</div>

<style>
.image-row {
  display: flex;
  gap: 10px;
  margin-bottom: 20px; /* spacing before stage plot */
}

.image-row img {
  flex: 1;
  min-width: 450px;
  height: auto;
  object-fit: contain;
}

.image-stageplot {
  display: flex;
  justify-content: center;
}

.image-stageplot img {
  max-width: 100%; /* adjust as needed */
  height: auto;
  object-fit: contain;
}

</style>


<div id="scrollTrack">
  <div id="verticalScrollProgress"></div>
</div>

<style>
#scrollTrack {
  position: fixed;
  top: 25%;
  left: 50%;
  transform: translateX(-700px);
  width: 5px;
  height: 50%;
  background-color: rgba(255, 255, 255, 0.1);
  z-index: 9998;
}

#verticalScrollProgress {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 0%;
  background-color: #5bff32;
  z-index: 9999;
}

</style>

<script>
window.onscroll = function() {
  const track = document.getElementById("scrollTrack");
  const bar = document.getElementById("verticalScrollProgress");
  
  const scrollTop = document.documentElement.scrollTop || document.body.scrollTop;
  const scrollHeight = document.documentElement.scrollHeight - document.documentElement.clientHeight;
  const scrollPercent = (scrollTop / scrollHeight) * 100;
  
  // Keep the green bar inside the track
  bar.style.height = scrollPercent + "%";
};
</script>







# *Personel*

Timothy Masso (me) - Alto Sax & Piano

Michael Golub - Trumpet

John Masso - Baritone Sax

Hana Igarashi - Piano 

Michael Gilbert - Bass

Balam Sarellano - Drums

# *Set List*

Free Improvised Piano and Drum Duo with Tim on Piano

Resolute - Composed by Timothy Masso

On A Clear Day - Composed by Burton Lane - Arranged by Timothy Masso

All The Things You Are - Composed by Oscar Hammerstein II - Arrnaged by Timothy Masso

Ninety Two - Composed By Timothy Masso

Untitled Graphic Score - Drawn by Timothy Masso


# Sheet Music

### Resolute - Composed By Timothy Masso

<iframe src="{{ site.url }}/assets/ResoluteCLead.pdf" width="100%" height="600px"></iframe>

### Nintey Two - Composed By Timothy Masso

<iframe src="{{ site.url }}/assets/92clead.pdf" width="100%" height="600px"></iframe>

### On A Clear Day - Composed by Burton Lane - Arranged by Timothy Masso

<iframe src="{{ site.url }}/assets/onacleardaylead.pdf" width="100%" height="600px"></iframe>



