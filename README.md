# how to create language or convert languge to xml object
https://www.cisco.com/c/en/us/td/docs/switches/datacenter/aci/apic/sw/2-x/rest_cfg/2_1_x/b_Cisco_APIC_REST_API_Configuration_Guide/b_Cisco_APIC_REST_API_Configuration_Guide_chapter_01.html

https://console.cloud.google.com/google/maps-apis/new?project=secure-path-242901&folder&organizationId

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



#  Excel Experince

https://www.geeksforgeeks.org/reading-excel-file-using-python/
"""
# Program extracting first column
import xlrd

loc = ("path of file")

wb = xlrd.open_workbook(loc)
sheet = wb.sheet_by_index(0)
sheet.cell_value(0, 0)

for i in range(sheet.nrows):
	print(sheet.cell_value(i, 0))
"""
