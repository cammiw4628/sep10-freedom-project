# Tool Learning Log

## Tool: Animate.css

---

### 3/3/25: Learning Log 1
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

### 3/10/25 Learning Log 2
 * I learned how to use **delayes** on `animate.css`
   *    Delays are used to **control** when the animation will start to play.
   *    Delays can be **directly added** to the element's class
   *    It will last to 1-5 seconds delays.
#### Delay Classes:
 * Delay for 2 seconds `animate__delay-2s`
 * Delay for 3 seconds `animate__delay-3s`
 * Delay for 4 seconds `animate__delay-4s`
 * Delay for 5 seconds `animate__delay-5s`
#### Delay on Text
For my texts I wanted my paragraph to play slower than the other animations but not too slow. I directly set the animation to be `animate__delay-2s` and my delay on the paragraph tag was able to work, it was much slower.
```HTML
 <p class="animate__animated animate__backInUp animate__slower animate__delay-2s center"> SLOWER TEXT Lorem ipsum odor amet, consectetuer adipiscing elit.
 Integer tristique fermentum ex nisi felis tortor..<p>
```
#### Delay on Images
I wanted my image to appear more slower than the paragraph tag and all the other animations. I added the class `animate__delay-4s` to my image, in order for my image to appear slower compared to other animates. My image animation will not play until the 4 seconds is over and then it will play the according animation.
```HTML
<img class="animate__animated animate__jackInTheBox animate__slower left animate__delay-4s" src="https://static.vecteezy.com/system/resources/thumbnails/018/742/203/small_2x/3d-minimal-world-cartoon-globe-3d-illustration-free-png.png" id="world" alt="" />
```
### 3/17/25: Learning Log 3
I learned how to use multiple animation to make my project more clear and presentable. 
#### What I Need to Know
 * Add a space when you are putting a class in an element in HTML
 * In your CSS put the same class name but instead of a space but a `.`
 * Make sure to always follow these rules for multiple animation factors.
#### HTML Code

```HTML
<h2 class="animate__animated animate__bounceIn animate__faster">Faster heading</h2>
```
#### CSS Code

```CSS
    .animate__animated.animate__hinge.animate__repeat {
                --animate-repeat: 3;
            }
```

### 3/24/25: Learning Log 4
I learned how to repeat my animation to **continue** repeating instead of a designated time.
 * Infinite: Goes on forever, no stop
 * Infinite class code name: `animate__infinite`
 * Can help attract outside users from the repeating animation
I have to keep in mind that this animation can annoy some users but I will try to use it effectively for my website for my users to not feel distracted by the repeating animation.

#### Infinite Text
I used a `p` tag for my text and made sure to include the class `animate__animated` before the infinite class animation of `animate__infinite`. This way my text will bounce non-stop for the rest of the time on my website.    
I have to also keep in mind an infinite animated text can be hard to read for users, so I have to keep using it wisely.
```HTML
<p class="animate__animated animate__bounce animate__infinite">Infinite text</p>
```
#### Infinite Image Animation
For my image, I found a image from an outside source of a sun and copied the URL and added my needed classes and the infinite class. My sun will be able to stand out a lot more to viewers because of the moving animation.
```HTML
 <img class="animate__animated animate__heartBeat animate__slower left animate__infinite sun" src="https://static.vecteezy.com/system/resources/previews/047/463/682/non_2x/cartoon-sun-transparent-background-free-png.png" id="sun" alt="sun" />
```

<!--

* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
