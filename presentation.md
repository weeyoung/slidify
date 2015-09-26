<style>
.main-slide {
    color: blue;
    font-size: 3em;
}
.sec-slide {
    color: black;
    font-size: 2em;
}
.footer {
    color: white; background: #000000;
    position: fixed; top: 90%;
    text-align:center; width:100%;
}
</style>

Shiny Chat with Word Frequency
========================================================
author: Wee Young Chua
date: 26 September 2015

Summary
========================================================
class:main-slide
This is a shiny application that contains the following function.
- Chat Application that tracks the chat since the creation
- Word Frequency of words that has been typed in the chat

Chat Application
========================================================
class:sec-slide
- Chat history is stored in file chat.Rds
- Chat text input goes into chat history etc
- Observe and sessions are being used
- Only shows the last 300 lines


Word Frequency
========================================================
class:sec-slide
- memoise is used to cached the words
- word history is stored in file words.Rds
= Chat text input goes into words.Rds and the word frequency is calculated
Using wordcloud_rep
- This can be shown here using 2 cat, 1 dog and 3 pigs (words)
![plot of chunk unnamed-chunk-1](presentation-figure/unnamed-chunk-1-1.png) 


Chat Application and Word Frequency
========================================================
class:sec-slide
- Chat application allows user to interact with each other. 
- Using word Frequency, we would be able to understand how user speaks
and interact with each other
- Over time, we would be able to predict and determine user behavior

<div class="footer" style="margin-top:-150px;font-size:80%;">
Copyright by Wee Young, Chua<br>
</div>
