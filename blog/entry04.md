# Blog Entry 4
##### 2/24/25
## Content and Sources
The tool I chose was [Animate.css](https://animate.style/) because animation is a tool that I would want to learn and incorporate into my project. Animation can make my project stand out more and feel appealing to other people viewing my work. I tinkered  with the tool by first doing the basic tutorial guided in the official website. After, I watched a video called [Animate.css the easiest animation library ever](https://youtu.be/VzbBcVRquYA?si=0PTfxOxvaJgiV0BV), which was extremely helpful to go over the basic guide on the website! When tinkering with the tool I also added other codes to make it more specific to what I want, such as how many times the animation will play and the duration of the animation. 
### Steps I Took Coding
#### Bounce
I started to work on making a bouncing animated text duration that lasted for 3 seconds, as well as the animation repeating 3 times. I made a class for a paragraph element called 'class="animate__animated animate__bounce animate__repeat-3"' and I made sure to do the same class into my css but removed the "-3" or else my code is unable to repeat. I used the css code " --animate-repeat: 3;" and "--animate-duration: 3s;" and my paragraph element was able to bounce and last for 3 seconds, also repeat 3 times.

#### Hinge

### Code snippets
#### HTML codes
```html
<h1 class="animate__animated animate__bounce animate__repeat-3 center">Animation practice</h1>
<h2 class="animate__animated animate__hinge animate__repeat-3 center">Hinge text</h2>
```
#### CSS codes
```CSS
            .animate__animated.animate__bounce.animate__repeat {
                --animate-repeat: 3;
                }
            h1 {
                --animate-duration: 3s;
            }

            .center {
                text-align: center;
            }
            .animate__animated.animate__hinge.animate__repeat {
                --animate-repeat: 3;
            }
            h2 {
                --animate-duration: 5s;
            }
```

### Code Product

## Skills
A skill I was able to develop is 

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
