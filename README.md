# Mars-News

Mars News – Module 11
For this project, I was able to integrate many concepts, along with skills of execution, from previous projects. These include knowledge of HTML element attributes, like the ability to identify between id and class, and to then use this to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup (the mention of which tends to make me hungry 😊).  I continue to hone my ‘scraping skills’, gleaning a cool collection of Mars atmospheric facts, evoking such curious questions like ‘What to wear while visiting my Martian brethren on typical spring day?????’.

Programmatic analysis was completed within the following two Jupyter Notebook modules:
1)	part_1_mars_news.ipynb
2)	part_2_mars_weather.ipynb
   
For part 1 (via the code from Jupyter Notebook #1 listed above), Mars news data was accessed from the website: https://static.bc-edx.com/data/web/mars_news/index.html.   

In particular, I extracted text elements and stored the ‘scraped’ results in a Python dictionary, and then added this to a Python list.

For part 2 (via the code from Jupyter Notebook #2 listed above), automated browsing was used to visit the Mars temperature data site: 
https://static.bc-edx.com/data/web/mars_facts/temperature.html. 

In particular, I created a yummy Beautiful Soup object and used it to scrape the data in the site’s Mars temperature table.  The scraped data was assembled into a Pandas dataframe, and then by way of nifty Panda functions, with both calculation and data visual construction, I was able to answer a plethora of curious ‘life on Mars’ questions.  For me, the most intriguing of these is that we’d all be half our age on Mars (specifically, 53% younger).  Less birthday parties in exchange for more youth sounds highly compensatory.  And yet, we’d all be freezing our young derrieres off.  The average temperature of Mars’ warmest month is a whoppin’ -68.38 degrees Celsius (that’s an even more frigid sounding -90.98 degrees Fahrenheit) – resulting in a more ‘frosty’ than ‘beautiful’ soup meal ☹.
