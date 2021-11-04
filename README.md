# Simple Ebay-Web-Crawler
![Web Crawler](https://www.simplilearn.com/ice9/free_resources_article_thumb/what_is_Web_Crawler.jpg)
<br />
<br />
The `ebay-dl.py` is tiny Python file that allows you to (although only simply) web-crawl the sepcific good that you are interested, going through each element of the good (name, price, shipping fee, if it is free-return, quality status, and quantity sold), downloading the first ten pages of the results and converting them into JSON or CSV file by those elements as you like.
<br />
<br />
To use this file, you will need to open `ebay-dl.py` in compitabible programming editor, change the working directory to which you save the file, and use the following command in the terminal:
<br />
```
$python ebay-dl.py 
```
<br />
<br />
##Examples:##
<br />
1. For my file 'rtx 3080.json' and 'rtx 3080.csv':
<br />
```
$python ebay-dl.py "rtx 3080"
```
<br />
and
```
$python ebay-dl.py "rtx 3080" --csv 1
```
2. 
