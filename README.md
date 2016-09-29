# Responsive-Book-Layout

Really cut it close with this one, having started seriously hacking away at the code only this morning (29th). 😂 

This was a project I had made a few years ago, but I'm still in the (slow) process of learning javascript and 98% of the time was spent on rewriting the original js from jQuery to vanilla js.

Originally I was using mordernizr to detect browser support but now use [CSS.supports](https://developer.mozilla.org/en-US/docs/Web/API/CSS/supports) and conditionally load the CSS for the book layout for screens at least 50em wide on a browser which supports CSS 3D transforms.

This was meant to be tumblr theme, the bare bones html was:

    <div id='posts'>
        <div class='post'></div>
        <div class='post'></div>
        <div class='post'></div>
        <div class='post'></div>
        ...
        <div class='post'></div>
    </div>
    
The previous version relied on jQuery to do some magic but it was taking me too much time to figure out how to port that part to vanilla. I'm noooot really good at solving problems.

The file size altogether comes close to almost 9kb! Just barely teetering over the edge. The html file is the largest, at 3.74 kb.

The files used in this project ordered by size:

script.min.js - 1.50 kb

book.min.css  - 1.64 kb

style.min.css - 1.67 kb

index.html    - 3.74 kb

------------------------

Total weighing in at 8.57 kb
