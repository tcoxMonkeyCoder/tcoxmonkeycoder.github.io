---
title       : Double the Value
subtitle    : 
author      : Taylor Wilcox
job         : Coursera Developing Data Products Course Project
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

The idea for my Shiny App was to allow the user to enter some numeric input, and then have the server double the value. I kept the idea super simple so I could just focus on learning the basics of Shiny.

To see this shiny app in action, click the link below:

https://tcoxmonkeycoder.shinyapps.io/DevelopingDataProducts/

---

## Details
1. User enters a value
2. Value is intercepted by the server
3. Server multiplies the value by 2
4. The original value and new doubled value are displayed to the user.

---

## Example

1. User enters 5
2. 5 * 2 = 10
3. User see's that the original value's double is 10


```r
5 * 2
```

```
## [1] 10
```

---

## Experience
Everything went pretty straight forward. I did run into one snag. I wanted to limit the max input number to be 100, which worked if the user uses the up arrow to increase the number, but there is nothing stopping the user from entering a value greater than 100 from the keyboard. It seems restricting the input in that sense might take more knowledge of javascript.

---

## Conclusion

Shiny seemed to be really easy to use. Even though my use case was about as simple as it gets, I didn't have to know much about html, css, javascript, or how to set up a server.


