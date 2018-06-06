# Shopify search results filter

A script that enables sorting or filtering search results in Shopify based on product titles and prices, it also supports filtering products in price ranges.

## Prerequisites
The script uses <a href="https://jquery.com/">jQuery</a> and <a href="https://github.com/js-cookie/js-cookie">JavaScript Cookies</a>

So make sure to include them in the theme.liquid file
```html
<script src="https://code.jquery.com/jquery-2.2.4.js" integrity="sha256-iT6Q9iMJYuQiMWNd9lDyBUStIq/8PuOW33aOqmvFpqI=" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/js-cookie@2/src/js.cookie.min.js"></script>
```

# Installing:

<ol>
  <li>Upload the <code>search-results-filter.js</code> file to the Shopify assets folder</li>
  <li>Copy <a href="https://github.com/Tarek-Mostafa/shopify-search-results-filter/blob/master/template.html">this HTML code</a>  to your <code>search.liquid</code> template or <code>search-template.liquid</code> section</li>
  <li>Copy <a href="https://github.com/Tarek-Mostafa/shopify-search-results-filter/blob/master/theme.liquid">this code</a> to your <code>theme.liquid</code> before the < /body> </li>
</ol>
