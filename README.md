# copper-sdk-html-sample

A simple html demo for Copper SDK

## Getting Started

1. serve this index.html through web server, you can do this by:
```bash
$ python -m SimpleHTTPServer 8080

# or if you prefer to use node.js
# npm install -g http-server
$ http-server
# or [RECOMMENDED]
$ http-server -S
```

2. Add an embedded app in Copper CRM

```
# if you serve the website using http, then it should be:
# URL: http://localhost:8080
URL: https://localhost:8080

Add to:
[x] People

Locations:
[x] Sidebar

# if serve the website using http
Optional Advanced Configuration:
{ "allowHttp": true }

```

3. Open browser and visit https://localhost:8080, allow visit

4. Go visit https://app.prosperworks.com and navigate to a people record!

Notice: if served through http, the app might be blocked by Chrome. You might need to enable running unsafe script in copper. Please check the right side of the address bar.
