# ProjectPP

## Analiza struktury opinii w serwisie Ceneo.pl

|Skladowa|Selektor|Zmienna|
-------------------------
|opinia|div.js_product-review|review|
|id_opinii|\[data-entry-id]\|id|
|autor|.user-post__author-name|author|
|rekomendacja|span.user-post__author-recomendation > em|recommendation|
|liczba_gwiazdek|span.user-post__score-count|stars|
|tresc|div.user-post__text|content|
|data_wystawienia|span.user-post__published > time:nth-child(1)\[datetime\]|published|
|data_zakupu|span.user-post__published > time:nth-child(2)\[datetime\]||purchased
|dla ilu przydatna|button.vote-yes > span |useful|
|dla ilu nieprzydatna|button.vote-no > span|useless|

|lista zalety|div.review-feature__col:has(>
div.review-feature__title--positives) >
div.review_feature__item|pros|