# Boomerang---SOAP-REST-Client

Input data
Product link: https://radio-shop.megaplan.by/
API documentation:

https://radio-shop.megaplan.by/api/v3/docs

Employee with director's rights:
Exploratory1@1.1 / Exploratory1@1.1

What should be done:
1. Install any REST client in the browser (example: Boomerang)

2. Create a new product using POST /api/v3/offer with the following data:
Commodity name: Ordinary commodity
Article: ART1
Price: 100
Currency: USD
Units of measurement: kg
VAT: 10%
other parameters at your discretion

3. Edit the product using POST /api/v3/offer/{id}. Change the following details
Item Name: Item Extraordinary
Price: 1000

4. Delete the created product using DELETE /api/v3/offer/{id}

What to send:
Screenshots with completed requests

Acceptance Criteria:
The screenshots show the following data:
- method
- query string
- complete request body
- full response body
