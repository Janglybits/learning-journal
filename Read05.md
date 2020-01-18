I've always been a believer that mastery comes from mistakes. I definitely made some mistakes with Lab05, but they helped make me aware of some easy to miss mistakes.

The first one that got me (and that I spent way too much time figuring out), is being careful to make sure that when you link your css in the head, that the file name is the same as the name of the css file. I know that it sounds obvious, but it can be easy to miss.  I was putting in 

<link href="css/styles.css" type="text/css" rel="stylesheet" />

Which would be great, except for the fact that my css file is named style.css

<link href="css/style.css" type="text/css" rel="stylesheet" />

The second one is font size.  I had reused some css from a previous project, and did't notice that font size was set to 0. I couldn't figure out why text wasn't visible until I inspected the page, and saw where it mentioned font-size: 0;

Clearing those up got things to where they needed to be