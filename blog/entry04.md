# Blog Entry 4
##### 2/24/25
## Content and Sources
The tool I chose was [Animate.css](https://animate.style/) because **animation** is a tool that I would want to learn and incorporate into my project. Animation can make my project stand out more and feel appealing to other people viewing my work. I tinkered  with the tool by first doing the basic **tutorial** guided in the official website. After, I watched a **video** called [Animate.css the easiest animation library ever](https://youtu.be/VzbBcVRquYA?si=0PTfxOxvaJgiV0BV), which was extremely helpful to go over the basic guide on the website! When tinkering with the tool I also added other codes to make it more specific to what I want, such as how many times the animation will play and the duration of the animation. I made a **bounce and hinge** animation text and here are the steps I was able to take.
## Steps I Took Coding
### Bounce
I wanted to make a **bouncing animated text** duration that lasted for 3 seconds and repeating 3 times. My first step was to make a `class` for an `h1` element called `class="animate__animated animate__bounce animate__repeat-3"`. The `-3` is for the **default iteration count** for the number of times the animation will repeat, in this case it is 3. In my `CSS` I did the same class but added a `.` between each space that was in my HTML, so it would look like `.animate__animated.animate__bounce.animate__repeat` and I removed the "-3" or else my code will be bugged. I used the CSS code `--animate-repeat: 3;` for the number of time I want the animation to repeat. I still had to make a duration for the bounce that lasted up to 3 seconds, so instead I went into my `CSS` and I used the element `h1` with the bounce and put `--animate-duration: 3s;` for 3 seconds that the code will play for. This allowed my code to work perfectly! If I were to place the duration code into my repeat class I made, the duration will not work because the class is _meant for repeat not the duration._ 

### Bounce HTML Code
```HTML
<h1 class="animate__animated animate__bounce animate__repeat-3">Animation practice</h1>
```
### Bounce CSS Code
```CSS
            .animate__animated.animate__bounce.animate__repeat {
                --animate-repeat: 3;
                }
            h1 {
                --animate-duration: 3s;
            }
```
### Hinge
I tinkered with some animation code that _Animate.css_ offered to us, one of them was _hinge_. Hinge is when the text is tilting, like it is about to fall off. The hinge code was **similar** to what we did with the bounce, but we replaced the bounce with hinge. I wanted the hinge text to last for 5 seconds and repeat 3 times, so we started by creating a class called `class="animate__animated animate__hinge animate__repeat-3"` in our `h2` element. The next step was to put the class into our CSS with `.` between the spaces from the HTML, so it was called `.animate__animated.animate__hinge.animate__repeat` and used the CSS code `--animate-repeat: 3;` to repeat hinge 3 times. I used the element `h2` and put `--animate-duration: 5s;` for the 5 second duration of the code. My hinge code was able to work and below are the codes to how I made the hinge code. 
### Hinge HTML codes
```HTML
<h2 class="animate__animated animate__hinge animate__repeat-3">Hinge text</h2>
```
### Hinge CSS codes
```CSS
            .animate__animated.animate__hinge.animate__repeat {
                --animate-repeat: 3;
            }
            h2 {
                --animate-duration: 5s;
            }
```

### Bounce and Hinge Code Product
![Screenshot 2025-03-02 7 35 32 PM](https://github.com/user-attachments/assets/e6ad5dd7-fc6a-4587-80a7-501b1a233e40)

## Skills
A skill I was able to develop is **learning basic animation** because _Animate.css_ was able to help me be guided to all the basic usage of CSS, which was very simple and clear to learn as a beginner of animating texts. After tinkering with the animation codes in my `IDE`, I was able to learn many simple ways of animating the text, such as hinge and bouncing texts. Another skill I was able to develop is **paying attention to details** because I was able to recognize the `.` in my CSS for animation that was in replace of the space in my HTML. This detail helped a lot in creating my animation in my CSS, which also allowed me to not have many bugs within the animations. 

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
