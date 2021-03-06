#  Web awareness of Library System
The vendor systems should provide robot.txt for indexing by 
[Google](https://google.com/),  [Bing](https://bing.com/), and 
other web indexers

## Comments from [Best Practice Review][BEST_PRACTICES] Topic ID #38
As much as possible, the patrons should be using or taken to a 
library-branded interface so they are not concerned with privacy or 
quality issues.

Library applications should have specialized SEO APIs that can be 
used to generate robots.txt and meta tags for increased SEO 
friendliness of OPAC and Discovery layers.

## FASTEN Alignment with [NCIP][NCIP]
Not applicable

## FASTEN Alignment with [LCF][LCF]

## FASTEN Alignment with [BIC Library Web Services][BICWS]

## FASTEN Alignment with [OpenID][OID]
Not applicable

## FASTEN Alignment with [ResourceSync][RS]
As [ResourceSync][RS] extends the [Sitemap](https://www.sitemaps.org/protocol.html) 
protocol, the FASTEN recommendation is to support the following REST verbs:

*   A **GET** request for `/robots.txt` returns a text file that links to the 
    `/sitemap.xml`, [source](http://www.openarchives.org/rs/1.1/resourcesync#robots)
*   A **GET** request for `/sitemap.xml` returns a valid and 
    well-formed xml document containing urls to available resources
*   A **GET** request for `/sitemapindex.xml` returns a valid
    and wel-formed xml document listing all of the available site maps
    published by the vendor. 


[BEST_PRACTICES]: https://docs.google.com/spreadsheets/d/1iQrdLVUSCW-0FWlrKNGjZJkB8nPO5Z94pg1Ie8GIKhg/
[NCIP]: http://www.ncip.info/
[OID]:  https://openid.net/
[RS]: http://www.openarchives.org/rs/toc
[LCF]: http://www.bic.org.uk/114/Library-Communications-Framework-(LCF)/
[BICWS]: http://www.bic.org.uk/files/pdfs/Library%20Web%20Services%20TandFWG%20Project%20Brief_Final%20v.1.1.pdf
