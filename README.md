# Laundry Services - Hero Image Animation

For this task, I updated the hero section of the Laundry app landing page to include a custom, attention-grabbing animation on the main image.

## My Learning Process

My first attempt at this animation had some issues, and I had to rework it to get the effects right. Here is what I learned:

1. **Creating a True Orbit:** Initially, I tried to make the image move in a circle by just using `translate(x, y)` at different percentages. That didn't work well—it moved in more of a diamond shape. I learned that to make a true circular orbit in CSS, you have to rotate the element, push it outward with `translateX`, and then apply a negative rotation so the image itself doesn't turn upside down. 
2. **The Squeeze Effect:** My first scale effect was too subtle (I used `scale(0.95, 1.05)`). To make it genuinely grab attention like the prompt asked, I adjusted the keyframes to stretch and squash much more dramatically using `scale(0.7, 1.3)` and `scale(1.3, 0.7)`. 

## How to Run

1. Make sure you have `index.html`, `style.css`, and the hero image saved in the same folder on your computer.
2. Double-click the `index.html` file to open it in your web browser.
3. Look at the washing machine image on the right side of the screen. It should automatically be moving in a smooth circular orbit while stretching and squashing.