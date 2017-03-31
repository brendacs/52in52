# 52 in 52: Log

## Week 1: 2/19/17 - 2/25/17

**This week's project**: [Meme viewer](https://github.com/brendacs/meme-viewer)

**Notes**: This was a suggestion from a friend since our university loves memes. I could visualize right away how I would create this and knew it wouldn't be too hard since it would require very little JavaScript. I was mostly right. It reminded me of how I made [Simple Clock](https://github.com/brendacs/simple-clock) and along the way I realized that I probably could have made the clock more efficient. I made some changes to the meme viewer's JavaScript after I initially finished because it showed images in the same order every time and stopped once it got to the end of the array of images. I learned how to generate random integers so that I could grab a random image from the array instead. I can see this project getting more complicated if I eventually carry out some other ideas I have for it in the future, but for now it's done. A simple but good start to the challenge I'd say!

## Week 2: 2/26/17 - 3/4/17

**This week's project**: [People generator](https://github.com/brendacs/people-generator)

**Notes**: I decided to work with APIs this week because there are a lot of websites/apps I want to create that are only possible with APIs. I started with a simple one that I came across called the Random User Generator which is usually for generating random users for databases. I skimmed through the documentation for it and an article that used it. Then I watched a tutorial and followed it in coding a super simple webpage using jQuery to work with API, JSON, and AJAX (I knew none of these four things). With those stepping stones and StackOverflow under my belt, I started to code this generator, and I can definitely say I learned so much from it this week. One part of this project, the JavaScript modals that show the rest of the random people's info, is still in progress, but otherwise it is pretty much done!

**Update**: Two days later, I finally finished those modals, and I'm very proud of this whole project!

## Week 3: 3/5/17 - 3/11/17

**This week's project**: [Whether weather](https://github.com/brendacs/whether-weather)

**Notes**: I had meant to work on a weather app for a while so this challenge gave me good motivation to. The API from OpenWeatherMap was no harder to work with than the Random User API, but a truly silly mistake stumped me for hours. In the end, I realized I didn't link to the JavaScript in the HTML... I was so relieved and actually quite ecstatic that it wasn't a problem with my code but also very annoyed at myself when I realized what the problem was. That aside, it was a fun project, and I feel very happy with it. Along the way, learned that bold color schemes work better on screens than muted colors, which I naturally lean towards; if there **has to be** muted colors, there should probably be some bright ones to counter it. Apart from design, I also got better at using jQuery to manipulate things. However, because I got stuck for so long, I didn't finish as much as I wanted to. In the near future, I want to add a toggle to switch from Farenheit to Celsius, a mini-survey about clothing preferences, weather picture animations, and make it mobile/tablet compatible. I might do some of this tomorrow since it's Sunday or during spring break. All in all, I am pretty satisfied with the outcome of this and am happy with the amount I have learned doing it. On to the next project!

## Week 4: 3/26/17 - 4/1/17

**This week's project**: [Newsworthy tab](https://github.com/brendacs/newsworthy-tab)

**Notes**: So I skipped two weeks... woops. To be fair, I had four midterms all in one week, interviews for startups (landed an internship!), and an esssay to write. You know what, as long as I finish 52 projects eventually and don't make too many excuses it should be fine, right? As a side note, some projects might take a bit longer because I'll be getting designs from one of my friends whose into graphic design and has a much better eye for design than I do.

Anyway, back to this week's project. This week, I practically did three projects in one: I created a Chrome extension that is a custom new tab page with weather, the latest top news, and a slide-out to-do list.

For weather, I used [simpleWeather.js](http://simpleweatherjs.com/) instead of the OpenWeatherMap API because it's more accurate and doesn't use http. To style the news slider, I used the [slick carousel plugin](https://github.com/kenwheeler/slick/) after giving up on making my own from scratch (I was at least 75% of the way there but it was taking too long and getting frustrating). For actually getting the top news headlines, links, and images, I used [NewsAPI](https://newsapi.org/). The to-do list animation is done with CSS3 and the functionality is all in jQuery, which I'm happy to have gotten really familiar with lately. To save data, I used localStorage for the first time, and it's really simple--in this case at least; I used to think it was complicated. To make it work as a Chrome extension, I had to do some trial and error with the [manifest.json](manifest.json). Besides all these things, I worked hard to make my CSS even more modular than I used to with SASS partials by separating reset, layout, typography, states, and the different main sections of the page. I also tried my best to write clean, clear and modular JS/jQuery though it could probably still be better. I used Grunt as usual to put it all together into concatenated, minified files.

I've been on StackOverflow and other sites what seems like 100 times for this project and you can see what I meant when I said it was like three projects in one because of all the different tools, APIs, and plugins I had to learn to use and everything I had to learn and accomplish to get features working the way I envisioned... all in three days. I think this makes up for the two weeks I missed. ;)

P.S. Once it's finished processing and is fully public, I'll add the link to the Chrome extension on the Chrome Store!
