Precondition
```
# Device is configured with proxy debugging software (Charles Proxy, ProxyMan, HTTP Toolkit etc.)

### Find and identify a collection on the Home Page for modification
2. Launch `<application>` on `<platform>`
1. Inspect and find the "discover_id" in the configurtion endpoint - https://tv-api-qa.redbull.com/v3/configuration/ios/v2_stv
3. Locate the product endpoint - https://tv-api-qa.redbull.com/products/v5/stv/en_US/at/PN-discover?os_family=ios&category=smartphone
4. Locate the featured collection ID
5. Locate and enable "Map Local" tool for the the collection endpoint - https://tv-api.redbull.com/collections/v5/rbtv/en_US/at/{ID}
6. Delete a card froim the collection and save the file
7. Enable the Local Map file

Setup Example (ProxyMan):
https://wcarey-ibeta.github.io/redbulltv/images/ios/contentrefresh/contentrefresh_proxyman_setup.mp4
```

Step 1:
```
# Verify page refresh on tab change
1. Navigate to the Events Page
2. Navigate back to home
```
```
The home page will refresh with with the updated collection

![](https://wcarey-ibeta.github.io/redbulltv/images/ios/contentrefresh/tabchange.gif)
```