**accounting.js** is a tiny JavaScript library for number, money and currency parsing/formatting. It's lightweight, fully localisable, has no dependencies, and works great client-side or server-side. Use standalone or as a nodeJS/npm and AMD/requireJS module.

Visit the plugin homepage for demos and documentation: **http://openexchangerates.github.io/accounting.js/**

Please checkout or download the latest stable tag before using in production. [Bug reports](https://github.com/openexchangerates/accounting.js/issues) and pull requests are welcome.

Maintained by [Open Exchange Rates](https://openexchangerates.org "Free reliable exchange rates/currency conversion data API") and originally by [@josscrowcroft](http://twitter.com/josscrowcroft) and other [contributors](https://github.com/openexchangerates/accounting.js/contributors).

This is a forked project from Accounting.js.  

Forked version has the following changes.

1.The toFixed precision method has precision values determined by exponentials.
2.Grouping currencies option has been introduced. The default value for grouping numbers is 3.
  e.g., 12,345,678.67  --> After the thousands place , the digits are grouped based on the given option.

---

### Works great with:

* **[money.js](http://openexchangerates.github.com/money.js "JavaScript and NodeJS Currency Conversion Library")** - a tiny (1kb) standalone JavaScript currency conversion library, for web & nodeJS
* **[Open Exchange Rates](https://openexchangerates.org "realtime and historical exchange rates/currency conversion data API")** - the free currency conversion data API


