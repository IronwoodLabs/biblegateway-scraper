# BibleGateway Scraper

This is a simple scrapper made with Python and BeautifulSoup.

## Usage:

`python app.py [verse] [bible version | optional, it defaults to NASB)`

So, on the terminal:
```bash
python app.py John3.16
```
Will get
``` John 3:16 New American Standard Bible (NASB)
16 “For God so loved the world, that He gave His [a]only begotten Son, that whoever believes in Him shall not perish, but have eternal life.

Footnotes:John 3:16 Or unique, only one of His kind


Cross references:John 3:16 : Rom 5:8; Eph 2:4; 2 Thess 2:16; 1 John 4:10; Rev 1:5
John 3:16 : Rom 8:32; 1 John 4:9
John 3:16 : John 1:18; 3:18; 1 John 4:9
John 3:16 : John 3:36; 6:40; 11:25f
```

If you want another bible version:
```bash
python app.py John3.16 ESV
```

Will get
``` John 3:16 English Standard Version (ESV)
For God So Loved the World
16 “For God so loved the world,[a] that he gave his only Son, that whoever believes in him should not perish but have eternal life.

Footnotes:John 3:16 Or For this is how God loved the world


Cross references:John 3:16 : Rom. 5:8; Eph. 2:4; 2 Thess. 2:16; 1 John 3:1; 4:9, 10
John 3:16 : See ch. 1:29
John 3:16 : Rom. 8:32
John 3:16 : ch. 10:28
```
