---
layout: page
title: ""
description: "CINVESTAV Sede Sur, Mexico"
feature_image: "/assets/images/projects_banner.png"
order: 6
---

<div id="image-grid" class="gallery-grid"></div>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/luminous-lightbox/2.3.2/luminous-basic.min.css">
<script src="https://cdnjs.cloudflare.com/ajax/libs/luminous-lightbox/2.3.2/Luminous.min.js"></script>

<style>
  .gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 12px;
    padding: 20px 0;
  }

  .gallery-item {
    position: relative;
    overflow: hidden;
    border-radius: 8px;
    aspect-ratio: 1 / 1; /* Keeps all thumbnails perfectly square */
    background: #f0f0f0;
  }

  .gallery-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.4s ease, filter 0.3s ease;
    display: block;
    cursor: zoom-in;
  }

  .gallery-item img:hover {
    transform: scale(1.1);
    filter: brightness(0.9);
  }
</style>

<script>
  const folderPath = "/assets/images/gallery/"; 
  const maxPhotos = 50; 
  const container = document.getElementById('image-grid');

  for (let i = 1; i <= maxPhotos; i++) {
    const fileName = `${i}.jpg`;
    const fullPath = folderPath + fileName;
    
    const img = new Image();
    img.src = fullPath;

    img.onload = function() {
      // Create a link wrapper for the Lightbox
      const anchor = document.createElement('a');
      anchor.href = fullPath;
      anchor.className = 'gallery-item luminous'; // 'luminous' class targets the script
      
      const thumb = document.createElement('img');
      thumb.src = fullPath;
      thumb.loading = "lazy";
      
      anchor.appendChild(thumb);
      container.appendChild(anchor);

      // Initialize Lightbox for this specific new element
      new Luminous(anchor);
    };

    img.onerror = function() {
      return; // Stop if the file doesn't exist
    };
  }
</script>
