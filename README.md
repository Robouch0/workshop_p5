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

Example :

![Recording 2024-04-28 at 00 06 22](https://github.com/Robouch0/workshop_p5/assets/114905866/1e0073a4-042b-4e9e-827c-c7557bbe3023)


# Part 2 - Data structure - Keep it up !


# Exercice 00 - Arrays 

Ok now that the basics are set, let's move on other important things like structure our data, first with arrays !

Arrays in JS are very powerful tools. They are what we call "objects" and they come with "methods" link to them, those are functions used to do things with the array.

Don't worry if you don't understand everything right away, try searching on the internet what can be done with JS array

The exercice is simple, display a grid made of squares, and when you click on them they change from blue to green (or any color that you'd like :)

Example : 

![Recording 2024-04-29 at 00 07 03](https://github.com/Robouch0/workshop_p5/assets/114905866/e45f33ac-cdbc-47d2-8b99-0f3d5631054c)


# Exercice 01 - Custom Objects

As you've seen in the exercice before, array are really useful object. 

But wouldn't it be nice to create your own custom objects ?

For this exercice you will have to make multiple ellipse grows and explode if they reach a certain size.

Search on the internet whats a class in Javascript and what's a constructor, then with those informations create your own Balloon class and handle multiple of them at the same time !

They could have different size, different position, different colors etc...

Example :

![Recording 2024-05-01 at 22 21 19](https://github.com/Robouch0/workshop_p5/assets/114905866/4c4ed056-e1f1-4102-aad3-388bde256480)
