---
layout: page
title: Tiger Med Company
description: AWS - Cloud solution for Tiger Med Company
img: assets/img/cloud/logo.png
importance: 6
category: work
---


## Methodology

AWS - Cloud solution for Tiger Med Company

Native architecture

Cloud Solution
<div style="color:red;font-size: 1.5em;">
  Click on image to expand
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="position: relative;">
        <img id="cloud-image" src="/assets/img/cloud/Cloud-Architecture.png" alt="Methodology" class="img-fluid rounded z-depth-1" style="width: 100%; height: auto; cursor: pointer;">
    </div>
</div>
<div style="color:red;font-size: 2em; text-align: right; margin-top: 10px;">
   Esc to fall back
</div>

<!-- The Modal -->
<div id="myModal" class="modal">
  <span class="close">&times;</span>
  <img class="modal-content" id="img01">
  <div id="caption"></div>
</div>

<style>
/* Style the Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
}

/* Modal Content (image) */
.modal-content {
  margin: auto;
  display: block;
  width: 100%;
  max-width: 100%;
  height: auto;
}

/* Caption of Modal Image */
#caption {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
  text-align: center;
  color: #ccc;
  padding: 10px 0;
  height: 150px;
}

/* Add Animation - Zoom in the Modal */
.modal-content, #caption { 
  animation-name: zoom;
  animation-duration: 0.6s;
}

@keyframes zoom {
  from {transform: scale(0)} 
  to {transform: scale(1)}
}

/* The Close Button */
.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #f1f1f1;
  font-size: 40px;
  font-weight: bold;
  transition: 0.3s;
}

.close:hover,
.close:focus {
  color: #bbb;
  text-decoration: none;
  cursor: pointer;
}
</style>

<script>
// Get the modal
var modal = document.getElementById("myModal");

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById("cloud-image");
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
  modal.style.display = "none";
}

// When the user presses the ESC key, close the modal
document.addEventListener('keydown', function(event) {
  if (event.key === "Escape") {
    modal.style.display = "none";
  }
});
</script>