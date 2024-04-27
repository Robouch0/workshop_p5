# Workshop - Discover p5 library and learn about JS

# Introduction
Hi, welcome to this workshop ! 
The main topics of today will be learning more about JavaScript and precisely about a library named [p5 JS].

This lib contains a collection of pre-written functions meant for creative coding.
It can simplify the process of creating simple interactive visuals quickly in a web browser.

Let's start ! 
First go to https://editor.p5js.org/

Documentation p5 lib : https://p5js.org/reference/

# Part 1 - The basics


# Exercice 00 - P5.js Editor

Ok you are now on a basic code editor, try to learn your way around it ! 
You should see two functions already written : 
``` setup() ``` and ``` draw() ```
Search in the documentation what their purpose are, and then try to change the background color and add a circle shape with a different color on it !

![image](https://github.com/Robouch0/workshop_p5/assets/114905866/abcdb43e-126a-4c78-9ef5-4c738ac190f8)


# Exercice 01 - Variables in JS 

Now we are gonna talk about variables in JavaScript ! Unlike his little brother TypeScript, JS does not need to precise a type before declaring a variable.
Because the type of the variable can dynamicly change while the programm is running.

In C you would write this : 

``` int nbr = 5; ```

In JS you could write this :

``` ███ nbr = 5; ```

Oh no, the keyword before nbr has been corrupted !!

I guess you need to search on the internet the different ways of writing a variable in JS :p

When you are done searching, try to create a variable to gradually change things on your image, for example the color of the circle, or his position !

# Exercice 02 - Mouse Events 

Ok it's cool we have circles, colors and all, but none of this is interactive, it's time to change that !

The exercice is simple, i want you to code a button and a slider, to add interaction with the background.

For example your button could turn off the light and put all the display color to black, while your slider could change the background color progressivly.

In order to do this your gonna have to learn how to check if a point is in a circle, how to get datas about your mouse position and if it's clicked, etcc...

<details>
  <summary> HINT 💡 </summary>
  Those P5.js functions may help you achieve your goals :
  
  > line() 

  > dist() 

  > constrain()

  > map()

  > mousePressed(), mouseReleased(), mouseDragged();
</details>

![Recording 2024-04-28 at 00 06 22](https://github.com/Robouch0/workshop_p5/assets/114905866/1e0073a4-042b-4e9e-827c-c7557bbe3023)

