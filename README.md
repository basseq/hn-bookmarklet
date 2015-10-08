# hn-bookmarklet
Integrated bookmarklet for tracking HN submissions and comments on remote articles.

### Information
Uses [HN Search](https://hn.algolia.com/) by Algolia to gather information on associated *Hacker News* submissions (comments, links, etc.). An easy way to:
* See if an article has been submitted (and submit it, if new)
* Return quickly to HN discussion

### Installing
Just copy the below to a new bookmarklet:

```javascript
javascript:(function(){var el=document.createElement('script');el.src='XXX';document.body.appendChild(el);})();
````

### Known Issues
* Doesn't work with Medium (and other sites with strict Content Security Policies)
