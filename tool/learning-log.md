# Tool Learning Log

## Tool: Animate.css

---

### 3/3/25:
 * I learned how to make use classes to create **faster or slower speed**, as well as having an image with animation!
    *   Here are the class names provided by animate.css with the speed.
#### Classes:
 * Slow text at 2 seconds `animate__slow`
 * Slower text at 3 seconds `animate__slower`
 * Fast text at 800 millisecond `animate__fast`
 * Faster text at 500 millisecond `animate__faster`
#### Faster and Slower

By adding the class `animate__faster` or `animate__faster` the speed of how long the animate will last for changes, which is similar to the **duration** of the animation because of the speed changing. My `h2` will be much faster compared to my `p` tag when it plays the animation.

```HTML
<h2 class="animate__animated animate__bounceIn animate__faster">Faster heading</h2>

<p class="animate__animated animate__backInUp animate__slower"> SLOWER TEXT Lorem ipsum odor amet,
consectetuer adipiscing elit. Integer tristique fermentum ex nisi felis tortor arcu accumsan..</p>
```

#### Image With Animation
Image with animation is the same as any other element because all you do is just add a class with the animation that you want to play, it does not matter if you want it to be fast or slow, there is a **variety** of options to choose from. Below is my code with an external image with a **slower** pace animation to it. 
```HTML
<img class="animate__animated animate__jackInTheBox animate__slower" src="https://static.vecteezy.com/system/resources/thumbnails/018/742/203/small_2x/3d-minimal-world-cartoon-globe-3d-illustration-free-png.png" id="world" alt="" />
```
<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
