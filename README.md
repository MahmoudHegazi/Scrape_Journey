# Scrape_Journey
https://stackoverflow.com/questions/55199526/website-to-be-scraped-has-varying-class-names


https://stackoverflow.com/questions/26435689/how-to-use-re-compile-with-class-in-beautifulsoup


# number one tool scrapy


1. scrapy shell "http://www.dmoz.org/Computers/Programming/Languages/Python/Books/"

2. response.xpath('//ul[@class="directory-url"]/li')
3. response.xpath('//ul[@class="directory-url"]/li').get()
4. response.xpath("//img[@id='PreviewImage']/@src").extract()
5. response.xpath("//img[@class='PreviewImage']/@src").extract()
6. view(response)






7.  https://stackoverflow.com/questions/39243009/scrapy-tutorial-example
8.  https://www.geeksforgeeks.org/pagination-using-scrapy-web-scrapping-with-python/
9.  https://stackoverflow.com/questions/16127692/how-can-i-fetch-img-src-attribute-by-scrapy
10. https://stackoverflow.com/questions/28174557/scrapy-xpath-select-elements-by-classname


## note:
1. some times you need do more than web scraping to scrap data (hard_work.py) (15 working hours for clear result 0errors)
https://www.odcec.lecco.it/www.odcec.lecco.it/archivio.html
