# Entry 6
##### 5/5/25

## Content and Sources
### MVP
In class, we started planning to create wireframes for our website to plan towards our MVP. The wireframes were used to plan out our website with no extreme detail before actually coding.  We created a wireframe for both mobile and computer, so that it can be accessible for all users to view the website. MVP is the **minimum viable product** that has the needed features for a website to be usable. I added components such as `list groups`, `carousel`, `navbar`, and `cards` from [Boostrap](https://getbootstrap.com/) to make my website look more appealing with some animation using my tool [Animate.css](https://animate.style/). I put animation in the beginning of my website to make it noticeable and I put animation on my logo that is on the navbar to be more creative with my navbar.
### Challenges and Takeaway
A challenge I experienced was that my cards were being pushed together and squished as the screen size got smaller. I was trying to find a way to make my cards stay in their column. I first tried changing the width but my cards still crumbled together and as the width became smaller the cards turned thin on computer screens that makes it harder to read.
#### Code and Screenshot
```HTML
<div class="card center" style="width: 25rem;">
```

![Screenshot 2025-05-10 7 51 24 PM](https://github.com/user-attachments/assets/62335614-c92d-405b-a77b-2608f2b5ff63)
### Solution
To fix this solution I started using something other than the `rem` unit and used `100%` instead because 100% will take up all the space to maintain responsiveness through each screen size. This allowed my cards to be in their designated column as I wanted to originally. 
#### Fixed Code and Screenshot
```HTML
<div class="card center" style="width: 100%;">
```
![Screenshot 2025-05-10 7 54 18 PM](https://github.com/user-attachments/assets/1186eceb-11e0-42a9-94a2-2b296da8f1c1)

## Engineering Design Process
We are currently in step 5 of _engineering design process_ because we are creating our website but we are moving towards step 6 to test out our website when we start to present them. But currently we are creating our website and trying to go **beyond our mvp** to be improved. I still need to make my website more responsive on both devices, mobile and computer, which will take up some time and try to fix any other errors that I have missed.

## Skills
A skill I developed was to always **try** out different possibilities because if I do not try, I will be limited to my field of knowledge when coding but I want to expand that knowledge. When I was creating my cards, I switched out `rem` with other units that I learned and soon went on to using `%` to determine the error in my cards. I will not know until I try. Another skill I learned was to **never give up** because I took a lot of time trying to figure out ways to fix my cards and it made me frustrated that I was unable to figure out a solution. But I never backed down and took up the challenge and kept moving forward, I was motivated to do this.           
[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
