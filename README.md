# MCU's CSS Styles for the Hostfully's Direct Booking Site

[![Lint Code Base](https://github.com/Mountain-Cabins-Utah/Hostfully-CSS/actions/workflows/linter.yml/badge.svg)](https://github.com/Mountain-Cabins-Utah/Hostfully-CSS/actions/workflows/linter.yml)
![https://www.jsdelivr.com/package/gh/Mountain-Cabins-Utah/Hostfully-CSS](https://data.jsdelivr.com/v1/package/gh/Mountain-Cabins-Utah/Hostfully-CSS/badge?style=rounded)

This repository stores Mountain Cabin Utah's CSS Styles for the Hostfully Direct Booking site.

📌 **Delivery Endpoint**

```url
https://cdn.jsdelivr.net/gh/Mountain-Cabins-Utah/Hostfully-CSS@main/style.css
```

## Directions to Update CSS Link on Hostfully

1. Please select `Agency Setting` => then choose `White Labeling` tab.

2. Tick on the box `White labelled Direct booking website` then you will see the area to put CSS link.

3. Copy and paste `Delivery Endpoint` URL into area.

### Purge CDN Cache
Simply send a `GET` request to `https://purge.jsdelivr.net/gh/Mountain-Cabins-Utah/Hostfully-CSS@main/style.css`; although the repo already has a GitHub Action Workflow that should clear the cache upon every new commit.
