---
layout: essay
type: essay
title: "Bootstrap 5: Should You Use It?"
# All dates must be YYYY-MM-DD format!
date: 2023-10-05
published: true
labels:
  - Bootstrap
  - Opinion
  - Software Engineering
---

## My Experience Learning To Use Bootstrap 5

![image](https://images.unsplash.com/photo-1518773553398-650c184e0bb3?crop=entropy&cs=tinysrgb&fit=max&fm=png&ixid=M3wxNDIyNzR8MHwxfHNlYXJjaHwxfHxib290c3RyYXAlMjBjb2RlfGVufDB8fHx8MTY5NjU4MDcwMHww&ixlib=rb-4.0.3&q=80&w=1080)

Bootstrap 5 is a popular front-end framework for creating responsive web designs - between 1/4 and 1/5 of the net uses some version. Bootstrap provides a wide range of pre-built components and styles, saving developers time and effort. One of the most convenient aspects of Bootstrap is its intentionality of being compatible with many screen sizes (think phones, tablets, and computers). This means you can create a single website that will look great on all devices without writing much extra code.

I recently started learning to use Bootstrap 5, and I was impressed with how easy it was to get started. I could create a simple website with a navigation bar, some text, and images in just a few minutes. I then practiced these by attempting to remake a website using Bootstrap 5. I picked one that I believe has lots of intentional and thought-through styling: the Riot Games homepage. I was largely successful, and the two sites look similar ([you can look at mine here](https://heinrichmaertens.github.io/RiotWebsiteBootstrap/)). However, my final code still used a lot of custom CSS (about a line of CSS per line of HTML). Many page components have distinctive styling that the native Bootstrap framework can't produce. For example, custom gradients, particular padding, and varying margins across sections. I also noticed that when I ran into these constraints with Bootstrap, I made much of the rest of the surrounding elements using CSS because switching between the two felt like a shift in programming style.

Further, I did not use Bootstrap for pseudo-elements and pseudo-classes. Since these seem to get more frequent as the styling becomes more intentional, this might be a limitation with using frameworks: while they are great to use, they may require lots of custom code if you want full customization. While ostensibly, most of the styling I did on my practice site is also possible via Bootstrap, it seems more challenging to implement, and the readability of the code is also somewhat lowered. One of the main tradeoffs of using Bootstrap is that you're sacrificing a less readable HTML file in place of having two things to look at. As all of the CSS code is in line with the standard HTML, it can get chaotic when setting 5+ different classes for a single HTML element.

Going back to the positives, what I appreciated about Bootstrap was how fast I could get something set up to work off of. That speed helped make getting started less intimidating. My takeaway is that Bootstrap 5 is a great framework to include for most websites. It is excellent for beginners and experienced developers; providing pre-built components and styles can seriously speed up development. However, it's important to be aware of its limits and to be prepared to use some of your own CSS if needed.

##### Here is a quick summary
##### **Pros**
- Save time and effort
- Create responsive designs easily
- Use consistent styling across your website
- Lots of community and developers support

##### **Cons**
- HTML can become less readable
- It may still require custom CSS for unique styling
- There is a learning curve to switch