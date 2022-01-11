# Troogle-A-Search-Engine-From-Students
This is a school project (CSD AUTh). Me and my collaborator had to design and implement a simple search engine, 
which will have the whole functionality of a large scale search engine.


1) In Crawler_Indexer_run.py where the execution of Crawler starts, inputs have to be read from user mannualy.
2) In the page, crawling starts the page has to be written mannualy, not with copy-paste
3) From each file we use theese libraries:

crawler.py: urllib, from urllib.request, urlopen and from bs4, BeautifulSoup.
Crawler_Indexer_run.py: threading, shutil and Queue from queue.
csv_handler.py: pandas, os.
file_handler.py: os.
find_links.py: from html.parser we use HTMLParser and from urllib, parse.
Index.py: re, string, stopwords fromnltk.corpus, WordNetLemmatizer from nltk.stem , and word_tokenize from nltk.tokenize.
QueryRun.py: re, string, stopwords fromnltk.corpus, WordNetLemmatizer from nltk.stem , and word_tokenize from nltk.tokenize.
server.py: logging, urllib, from http.server, SimpleHTTPRequestHandler and HTTPServer and from bs4, BeautifulSoupp.
Similarity.py: csv, math, και pandas.

4) To start Troogle search engine we run server.py and then we are going to localhost in 8080 port. There wr write
our query, how many pages we want in return (top-k) and then we search.

5) we run it in PyCharm Conda 3 intepreter.

There is also a PDF with the presentation of the tasks we had to do in Greek
