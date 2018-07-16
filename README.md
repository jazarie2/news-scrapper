# news-scrapper
generic library returning news extracted from news sources using python BeautifulSoup &amp; selenium

Code will focus on
- extraction of information body from rest of the page
- send information to mqtt chat protocol
- AWS lambda friendly.

This code is intended to allow news post processing would be better handled with divide & conquer methodology.
post processing will be expected to subscribed to MQTT messages as required.
example of usage:-
information such as bitcoin news, shall be process and cross meshed with financial news.
information such as political, shall be process in extraction facts against opinion
I intended this to be also used in conjunction with NLP to allow news extraction to be digested virtually