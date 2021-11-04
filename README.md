# Simple Ebay-Web-Crawler
![Web Crawler](https://www.simplilearn.com/ice9/free_resources_article_thumb/what_is_Web_Crawler.jpg)
<br />
<br />
The `ebay-dl.py` is tiny Python file that allows you to (although only simply) web-crawl the sepcific good that you are interested on Ebay, downloading the first ten pages of the good's search result, going through each element of the good (name, price, shipping fee, if it is free-return, quality status, and quantity sold), and converting them into a JSON or CSV file with the name of your search term and sorted by the said elements.
<br />
<br />
To use this file, you will need to open `ebay-dl.py` in compitabible programming editor, change the working directory to which you save the file, and use the following command in the terminal:
<br />
```
$python ebay-dl.py 
```
**Examples**:

1. For my files 'rtx 3080.json' and 'rtx 3080.csv':
```
$python ebay-dl.py 'rtx 3080'
```
```
$python ebay-dl.py 'rtx 3080' --csv 1
```
2. For my files 'Sennheiser.json' and 'Sennheiser.csv':
```
$python ebay-dl.py 'Sennheiser'
```
```
$python ebay-dl.py 'Sennheiser' --csv 1
```
3. For my files 'The Conquest of Bread.json' and 'The Conquest of Bread.csv':
```
$python ebay-dl.py 'The Conquest of Bread'
```
```
$python ebay-dl.py 'The Conquest of Bread' --csv 1
```

***Side Notes:**
1. The `--csv` command appears to indicate that the file will be made into a CSV file; the value behind it must be added and must be truthy (i.e anything numeric but 0) for it to work
2. Rmember to quote your search term when entering to avoid error
<br />

[The Course Project](https://github.com/mikeizbicki/cmc-csci040/blob/2021fall/hw_03/README.md)
