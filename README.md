# Rightmove-Sold

<h2>Description</h2>
The whole idea behind this project is to make certain checks very quick this is a building block for basic webscraping and checking agasint a excel sheet, for many of you who come across this may never have a need for this exact code but can take sections of this code to use for your own ideas or projects. I needed this to eleminate the time-consuming task of having to go onto rightmove sold and making sure that i have all the latest titles.
<br />
<h3>What to focus on</h3>
The focus for this should be on the "get_rightmove_data"  this uses selenium which is an automation tool for web based applications. In this case i use options and web browser to configure and start a chrome instance in headless browser mode ( without the GUI). Then using BeautifulSoup I parse the HTML content of the webpage fetched by Selenium. Card elements is used to identify where to extract the data from in HTML you can inspect the page and see the class and what the tag is and replace as you need.
<br/>
<h3></h3>
The only draw back to this is that you have to hardcode the links inside this program as i know i will never need to change the link im scraping from this was fine for me but im sure there is an easy way to input a name and use selenium to generate a link to your website. If you do need to use this exact code what it does it takes all property cards extracts just the price and stores them along with the property number and "cleans" the price essentially leaving only the interger value and then compares it to the values in my excel sheet if they arent an exact match it will flag as missing.


<h2>Languages Used</h2>

- <b>Python</b> 

<h2>Libaries Used </h2>
- <b>Re</b>

-<b>Fuzzywuzzy</b>
</br>
-<b>Selenium</b>
</br>
-<b>BS4</b>


