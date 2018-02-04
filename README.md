How to run the application : 
1. go to https://sarasaj.github.io/. and you'll see the main porfilio page.
2. go https://sarasaj.github.io/views/pizza.html to view the pizza project.

Optimizations made in index.html:
1. used github pages to upload the web pages it's much faster and with changes i made i scored 99 on mobile and 93 on desktop .. with ngrock it was 67 on mobile and 90 on desktop! big diffrence.
2. optimzed and compressed the images using photoshop , online tool and page speed files.
3. make analytics.js run async and removed google fonts .
4. add media attribute to print.css
5. inline css in the pages insted of an external file. 

Optimizations made in pizza project:
1. optimzed and compressed the images using photoshop , online tool and page speed files.
2. inline css in the pages insted of an external file. 
3. make main.js run at the end of html page.
4. remove any layout triggers out of the loop where needed.
5. replace querySelector with getElementById and querySelectorAll with getElementsByClassName
6. minmize the number of flying pizzas genrated.
7. debouncing the scroll event useing requestAnimationFrame 
8. storing elemnts and arrays or global varibales that are accessed many times. 
9. denested functions inside resizePizzas and removed determine dx 
10. storing any array length called in a loop in a local variable.
11. using backface-visibility: hidden; , transform: translateZ(0); for faster css.
12. calculating the number of random pizzas based on screen height.