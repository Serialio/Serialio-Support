# Web Form Rules
## Access The WFR Manager
1. Open the sidebar menu by swiping from the left edge of the screen to the center of the screen. 
2. Tap on "Settings."
![](https://i.imgur.com/AweUy5x.png)
3. Tap on "WEB Form Rules."
![](https://i.imgur.com/bqgH3k1.png)
4. You are now on the Web Form Rules Manager view!
![](https://i.imgur.com/24NfF2O.png)
## Enable Always Showing the Address Bar
To enable always showing the address bar, select the checkbox to the left of "Always show address bar."

![](https://i.imgur.com/yUvOhbh.png)
## Add a New WFR
To add a new Web Form Rule, tap on the plus symbol below the list of existing Web Form Rules.

![](https://i.imgur.com/lxWwyEp.png)

iScanBrowser will ask you if you would like to use the WFR wizard. 

![](https://i.imgur.com/XUyheUg.png)
### Without the WFR Wizard

![](https://i.imgur.com/QDlqR9L.png)

### With the WFR Wizard

![](https://i.imgur.com/gRdimPd.png)

#### Define URL Before and After Scan 
One of the WFR wizard options lets you use the scan data as part of the URL . You define the prefix and suffix of the URL.

A common implementation of this WFR template is to use the scan data as a parameter in a URL to look up products via a UPC code or another unique identifier.

For example:
https://www.amazon.com/s/ref=nb_sb_noss_2?url=search-alias%3Daps&field-keywords=[SCAN DATA]  

![](https://i.imgur.com/Wu6X1Vh.png)

#### PDF Auto-fill
Another WFR wizard template is the PDF Auto-Fill option. This template allows you to auto-fill a PDF form with scan data. 

![](https://i.imgur.com/3uPTzqw.png)

The WFR wizard auto-detects fillable form fields from the PDF's URL address and walks you through mapping the form fields.

![](https://i.imgur.com/ACEX38h.png)

Example of detected fields:

![](https://i.imgur.com/7SXXLBA.png)


Data mapping options for the detected fields:

![](https://i.imgur.com/gIaRzK3.png)

### Delete a WFR
To delete an existing Web Form Rule, tap on the "X" to the right of the WFR's name.

![](https://i.imgur.com/WpJnEWw.png)

