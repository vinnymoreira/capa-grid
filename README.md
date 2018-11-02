# Capa Grid
Capa is a responsive lightweight CSS grid based on a 10-column grid system where each column has a width of 10% that together add up to 100%.

<a href="https://vinnymoreira.com/capa-responsive-css-grid-demo/">Click here</a> to see a demo of Capa Grid.

## How to Use Capa Grid ##

Download Capa Grid and include the stylesheet file in the <em>< head ></em> tag.

The syntax for Capa CSS Grid is based a very simple concept. Most CSS classes start with a letter to represent a device (c, d, t, m), followed by a number to indicate a percentage.

### Available grid letters: ###

<ul>
  <li>"c" - Capa, or column (default)</li>
  <li>"d" - Desktop (1160px > d > 768px)</li>
  <li>"t" - Tablet (768px > t > 420px)</li>
  <li>"m" - Mobile (m < 420px)</li>
</ul>

### Available Numbers: ###

Multiples of 5, the numbers 33 and 66.

~~~html
5, 10, 15, 20, 25, 30, 33, 35, 40, 45, 50, 55, 60, 65, 66, 70, 75, 80, 85, 90, 95, and 100.
~~~  

#### Example: ####

~~~html
<div class="container">
  <div class="c70 t100">
      70% width div, 100% width on tablets, as well as mobile devices.
  </div>
  <div class="c30 t100">
      30% width div, 100% width on tablets, as well as mobile devices.
  </div>
</div>
~~~
