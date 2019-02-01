# web-scraping-with-puppeteer

### Links

[Web Scraping with Puppeteer](https://blog.bitsrc.io/web-scraping-with-puppeteer-e73e5fee7474)

### Notes

When calling `page.evaulate`, the code side the function actually gets passed to and run in
the browser execution environment.  Therefore it doesn't have access to any variables outside
the scope fo the function, and console.log statement don't appear in the node context, but in
the Chrome console.
