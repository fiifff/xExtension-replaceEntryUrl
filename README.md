# replaceEntryUrls extension

This FreshRSS extension . This plugin can be used to fetch and replace URLs in subscriptions with specific content. The content will completely replace the fetched page. Usually used to handle cases where the content retrieved via XPath from an article only includes a single title.

To use it, upload this entire directory to the FreshRSS `./extensions` directory on your server and enable it on the extension panel in FreshRSS.

## Changelog

* 0.1

## Configuration settings

* `replace domain` (default: `[]`):This option is a JSON object used to match the domains that need to be replaced. 
- For example: 
  - {"example.com":"//article"}
  - {"example.com":"//article","zzz.com":"//div",...}






