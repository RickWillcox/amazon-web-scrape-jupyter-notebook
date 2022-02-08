## Amazon Web Scraper

Second last cell on Jupyter-Notebook is the whole code together

Against Amazon ToS use at your own risk.

Takes in your search term and gives you the Description, Price, Rating, Review Count and Url of every listing up to 20 search pages (amazons limit)

It then saves your results to a csv file - example below

![image](https://user-images.githubusercontent.com/53924507/152954187-003b01d6-7492-4095-83a8-d019bdfce167.png)

There is probably a few bugs so test and adjust.

You will need to point this line `ser = Service("C:\\Program Files\\geckodriver.exe")` to the location your geckodriver.exe is
Code is made for firefox, you need to use different driver code for other browsers (although it is very similar). Just google selenium + webdriver + your browser for info.
