 A fully responsive, visually immersive 3D image carousel built with just HTML and CSS. 
Elegant, lightweight, and perfect for portfolios, galleries, and modern landing pages. 
 Hosted with GitHub Pages or Netlify 
✨ Features 
 ✅ Pure HTML & CSS — no JavaScript required 
 ✅ 3D image rotation using rotateY and translateZ 
 ✅ Customizable via CSS variables (--position, --quantity) 
 ✅ Responsive design using vh units 
 ✅ Easy to integrate into any frontend project 
 ✅ Clean, modern, scalable layout 
�
� Folder Structure 
3d-image-carousel/ 
├── index.html              
├── style.css               
# Main HTML structure 
# CSS styling & 3D transformations         
└── images/                
├── dragon1.jpg 
├── dragon2.jpg 
└── ... 
�
� Getting Started 
Clone & Run Locally 

 # Carousel image assets 
git clone https://github.com/hiruy72/3d-image-carousel.git 
cd 3d-image-carousel 
open index.html  # or drag into your browser 
�
� How It Works 
The magic is in the transform function: 
transform: 
rotateY(calc((var(--position) - 1) * (360deg / var(--quantity)))) 
translateZ(550px); - --position: The image's index in the carousel - --quantity: Total number of items - rotateY: Spreads the images around a circular Y-axis - translateZ: Pushes the items outward in 3D space 
�
� Easily Customizable 
<div class="slider" style="--quantity: 8"> 
<div class="item" style="--position: 1;"><img src="img1.jpg" /></div> 
... 
</div> 
�
� Responsive Design 
• The .slider uses 80vh for flexible vertical scaling 
• Images automatically fit and maintain aspect ratio with object-fit: cover 
�
� Built With 
 ✅ HTML5 
 ✅ CSS3 (Transforms, Variables, Flex) 
 ✅ Bootstrap 5 (optional for layout responsiveness) 
�
�🌐 Author 
**Hiruy Legesse Adane** 
�
� Addis Ababa, Ethiopia 
�
� hiruyadane@gmail.com 
�
� LinkedIn: https://linkedin.com/in/hiruy-legesse 
GitHub: https://github.com/hiruy72 
�
� License 
This project is licensed under the MIT License — feel free to use, modify, and distribute. 
�
� Support & Feedback 
If you like this project: 
• 📸 Star it on GitHub 
• 📸 Share it with other developers 
• 📸 Drop your feedback via issues or email 
