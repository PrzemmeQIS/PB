# PB
## CeneoScrapper
## [Ceneo.pl](https://www.ceneo.pl/)
|Składowa                |Selektor               |Nazwa zmiennej|
|........................|...................................................|..............|
|Opinia                  |li.js_product-review                               |              |
|id opinii               |["data-entry-id"]                                  |              |
|autor                   |div.reviewer-name-line                             |              |
|rekomendacja            |div.product-review-summary > em                    |              | 
|ocena                   |div.review-source-count                            |              |
|treść opinii            |p.product-review-body                              |              |
|lista wad               |div.cons-cell > ul                                 |              |
|lista zalet             |div.pros-cell > ul                                 |              |
|przydatna               |button.vote-yes > span                             |              |
|nieprzydatna            |button.vote-no > span                              |              |
|data wystawienia opinii |span.review-time > time:first-child["datetime"]    |              |
|data zakupu             |span.review-time > time:nth-child(2)["datetime"]   |              |

## 