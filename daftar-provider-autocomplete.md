# Daftar website penyedia autocomplete

Bisa dipake untuk generate keyword :) 

```js
providers = {
        duckduckgo: "https://duckduckgo.com/ac/?q=${query}",
        google: "http://suggestqueries.google.com/complete/search?client=chrome&hl=${lang}&gl=${country}&callback=?&q=${query}",
        "google news": "http://suggestqueries.google.com/complete/search?client=chrome&hl=${lang}&ds=n&gl=${country}&callback=?&q=${query}",
        "google shopping": "http://suggestqueries.google.com/complete/search?client=chrome&hl=${lang}&ds=sh&gl=${country}&callback=?&q=${query}",
        "google books": "http://suggestqueries.google.com/complete/search?client=chrome&hl=${lang}&ds=bo&gl=${country}&callback=?&q=${query}",
        youtube: "http://suggestqueries.google.com/complete/search?client=chrome&hl=${lang}&ds=yt&gl=${country}&callback=?&q=${query}",
        "google videos": "http://suggestqueries.google.com/complete/search?client=chrome&hl=${lang}&ds=v&gl=${country}&callback=?&q=${query}",
        "google images": "http://suggestqueries.google.com/complete/search?client=chrome&hl=${lang}&ds=i&gl=${country}&callback=?&q=${query}",
        yahoo: "https://search.yahoo.com/sugg/ff?output=jsonp&appid=ffd&callback=?&command=${query}",
        bing: "http://api.bing.com/osjson.aspx?JsonType=callback&JsonCallback=?&query=${query}",
        ebay: "http://autosug.ebay.com/autosug?_jgr=1&sId=0&_ch=0&callback=?&kwd=${query}",
        amazon: "http://completion.amazon.co.uk/search/complete?method=completion&search-alias=aps&mkt=4&callback=?&q=${query}",
        "kindle store": "http://completion.amazon.com/search/complete?method=completion&mkt=1&search-alias=digital-text&q=${query}",
        wikipedia: "http://en.wikipedia.org/w/api.php?action=opensearch&search=${query}",
        twitter: "https://twitter.com/i/search/typeahead.json?count=30&result_type=topics&src=SEARCH_BOX&callback=?&q=${query}",
        baidu: "http://suggestion.baidu.com/su?cb=?&wd=${query}",
        yandex: "https://yandex.com/suggest/suggest-ya.cgi?callback=?&q=?&n=30&v=4&uil={lang}&part=${query}",
        "google play store": "https://market.android.com/suggest/SuggRequest?json=1&c=0&hl=${lang}&gl=${country}&callback=?&query=${query}",
        "google play store apps": "https://market.android.com/suggest/SuggRequest?json=1&c=3&hl=${lang}&gl=${country}&callback=?&query=${query}",
        "google play store movies": "https://market.android.com/suggest/SuggRequest?json=1&c=4&hl=${lang}&gl=${country}&callback=?&query=${query}",
        "google play store books": "https://market.android.com/suggest/SuggRequest?json=1&c=1&hl=${lang}&gl=${country}&callback=?&query=${query}"
    }
```