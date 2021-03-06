# What TV should you buy? (2021 edition)

What TV should you buy? (2021 edition), is aimed at people who are looking to buy a TV and are having trouble navigating around the OLED vs QLED battle. This quiz hopes to simplify the process by asking a few questions and giving very straight answers. This is mainly targeted at people who are either tech illiterate, or know very little in regards to TV tech. Not only does the quiz aid in choosing the TV, but also has handy descriptions of what each technology does.

## Features 
There are many features within this site, the main one being the quiz, I shall go through the many features below.
### Existing Features

- __The Nav Bar__

  - Stuck to the top of each page, the nav bar allows for easy navigation across the site, with very little trouble. Hamburger menu included for mobile, and is fully responsive, with hover over text.

![Nav Bar](assets/imgs/nav_bar.png)

- __The Quiz__

  - This section allows the user to play an interactive quiz to find out which TV they need.
  - By clicking on the answers, the user's input is recorded and stored in an array, to give a more accurate TV recommendation. 

![Quiz](assets/imgs/the_quiz.png)

- __The Interactive Table__

  - The interactive table includes the manufacturer, the Model number, the RRP and an Amazon link. 
  - Using Tabulator, the entire table is completely interactive and sortable.

![Table](assets/imgs/table.png)

- __OLED vs QLED__

  - The OLED vs QLED page displays both, OLED and QLED, and gives the pros and cons in the form of cards on the screen. The user can scroll forward and back between the cards and read as they go along. 

![Cards](assets/imgs/cards.png)

Additional features that I would implement would be:
 - 2022 models
 - Better accuracy of model recommendation
 - More questions on quiz

### Features Left to Implement

- TV newsfeed displaying all new advancements in the TV industry, that is live updating from Twitter, showing anything from Samsung Displays, or LG Displays etc.

## Testing 

In regards to testing, having multiple people complete the quiz, and then further trying every combination myself, allowed to validate the quiz as BUGFREE. The table has also been thoroughly tested with the only problem so far being resizing of the columns with no way to reset other than a page refresh (F5). In regards to the OLED vs QLED cards, the testing was done mainly with console.log() functions, detailing exactly what the site is doing so as to know where problems may have arised.


### Validator Testing 

- HTML
    - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=http%3A%2F%2F34.73.3.134%2Fwhat-tv-do-you-need%2F)
- CSS
    - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=http%3A%2F%2F34.73.3.134%2Fwhat-tv-do-you-need%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- JavaScript
    - No errors were found when passing through the official [Jshint validator](https://jshint.com/)
      - The following metrics were returned: 
      - There are 17 functions in this file.
      - Function with the largest signature take 1 arguments, while the median is 0.
      - Largest function has 23 statements in it, while the median is 4.
      - The most complex function has a cyclomatic complexity value of 9 while the median is 4.

### Unfixed Bugs

No unfixed bugs.

## Deployment

- The site was deployed to Google Cloud Platform. The steps to deploy are as follows: 
  - Create a Virtual Machine
  - Install NGINX on VM
  - Using Linux command prompt, install and upload files to server, allowing for reading and display of content 

The live link can be found here - http://34.73.3.134/what-tv-do-you-need/index.html


## Credits 

### Content 

 - [Tabulator](http://tabulator.info/) - Tabulator allowed for fully featured, interactive JavaScript tables.
 - [Bootstrap](https://getbootstrap.com/) - Bootstrap allowed for easy styling, and easy responsiveness. 

### Media

 - [QN94A picture](https://www.samsung.com/uk/tvs/qled-tv/qn90a-50-inch-neo-qled-4k-smart-tv-qe50qn90aatxxu/) - Taken from Samsung.com
 - [LG C1 picture](https://www.lg.com/uk/tvs/lg-oled65c14lb) - Taken from LG.com
