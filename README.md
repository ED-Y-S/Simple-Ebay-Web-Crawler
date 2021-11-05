# Simple Ebay-Web-Crawler
![Web Crawler](https://www.simplilearn.com/ice9/free_resources_article_thumb/what_is_Web_Crawler.jpg)
<br />
<br />
The `ebay-dl.py` is tiny Python file that allows you to (although only simply) web-crawl the sepcific good that you are interested on Ebay, downloading the first ten pages of the good's search result, going through each element of the good (name, price, shipping fee, if it is free-return, quality status, and quantity sold), and converting them into a JSON or CSV file with the name of your search term and sorted by the said elements.
<br />
<br />
To use this file, you will need to open `ebay-dl.py` in a compitabible programming editor, change the working directory to which where you save the file, and use the following command in the terminal:
<br />
```
$python ebay-dl.py "search term"
```
or
```
$python ebay-dl.py "search term" --csv 
```
**Examples**:

1. For my files 'rtx 3080.json' and 'rtx 3080.csv':
```
$python ebay-dl.py 'rtx 3080'
```
```
$python ebay-dl.py 'rtx 3080' --csv
```
2. For my files 'Sennheiser.json' and 'Sennheiser.csv':
```
$python ebay-dl.py 'Sennheiser'
```
```
$python ebay-dl.py 'Sennheiser' --csv
```
3. For my files 'The Conquest of Bread.json' and 'The Conquest of Bread.csv':
```
$python ebay-dl.py 'The Conquest of Bread'
```
```
$python ebay-dl.py 'The Conquest of Bread' --csv
```

***Side Notes:***
1. Typing the `--csv` command a space after the search term to indicate that the file will be created into a CSV file instead of a JSON file.
2. Rmember to quote your search term when entering to avoid error that might be caused by a space in between words.
3. By default, `ebay-dl.py` only goes through the first ten pages of the search results on Ebay. However, you may add `--page_number` behind the search term (before `--csv` if you have it) with the amount of pages you want one space behind it.
<br />

[The Course Project](https://github.com/mikeizbicki/cmc-csci040/blob/2021fall/hw_03/README.md)
