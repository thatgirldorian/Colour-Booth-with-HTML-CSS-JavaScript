# Colour-Booth-with-HTML-CSS-JavaScript

<h3>Challenge faced:</h3>
  - I had problems with getting the background image to render. I grabbed a nice photo from unsplash.com and linked to it with the CSS         properties below:
         *
          body {
          margin: 0;
          color: rgba(255,255,255,0.9);
          background: url("https://unsplash.com/photos/0-frPETzEVs") 0 100%/340px no-repeat, var(--primary-color);
          font-family: 'Varela Round', cursive;
          }
          
<h3>Solution:</h3>
- I looked at the css-tricks.com website and searched how to make it work. I was able to get it to work with the following CSS code:
          *
          body { 
          margin: 0;
          color: black;
          background: url(image/flowers.jpg) no-repeat center center fixed; 
          -webkit-background-size: cover;
          -moz-background-size: cover;
          -o-background-size: cover;
          background-size: cover;
          font-family: 'Varela Round', cursive;
          }  
          
