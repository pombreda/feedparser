# About #

feedparser is a Python library that parses feeds in all known formats, including Atom, RSS, and RDF. It runs on Python 2.4 all the way up to 3.3.

# Latest release #

feedparser 5.1.3 (December 9, 2012)

  * Consolidated and simplified the character encoding detection code
  * [Issue 346](https://code.google.com/p/feedparser/issues/detail?id=346) (the gb2312 encoding isn't always upgraded to gb18030)
  * [Issue 350](https://code.google.com/p/feedparser/issues/detail?id=350) (HTTP Last-Modified example is incorrect in documentation)
  * [Issue 352](https://code.google.com/p/feedparser/issues/detail?id=352) (importing lxml.etree changes what exceptions libxml2 throws)
  * [Issue 356](https://code.google.com/p/feedparser/issues/detail?id=356) (add support for the HTML5 attributes `poster` and `preload`)
  * [Issue 364](https://code.google.com/p/feedparser/issues/detail?id=364) (enclosure-sniffing microformat code can throw `ValueError`)
  * [Issue 373](https://code.google.com/p/feedparser/issues/detail?id=373) (support RFC822-ish dates with swapped days and months)
  * [Issue 376](https://code.google.com/p/feedparser/issues/detail?id=376) (uppercase 'X' in hex character references cause `ValueError`)
  * [Issue 382](https://code.google.com/p/feedparser/issues/detail?id=382) (don't strip inline user:password credentials from FTP URL's)