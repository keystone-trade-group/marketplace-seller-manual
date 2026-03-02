# Return Merchandise Authorization for non-resident Amazon.ca Sellers

## Background
- RMAs for merchant-fulfiled Amazon.ca orders must be manually approved
- apparel returns should be free to the customer

## Prerequisites
A PDF-to-image converter (Amazon doesn't allow upload of PDF return labels). For Windows, run:
```winget install clawSoft.clawPDF``` in Powershell


## Actions
- Go to https://sellercentral.amazon.com/gp/returns/list/v2
- Filter by "Pending actions" and "Canada" in the dropdowns
- For each order:
  - open "More information" to view postal codes
  - Get return label shipping quotes using postal codes and original shipment dimensions. Try:
    - [Canada Post](https://www.canadapost-postescanada.ca/shippingtools-outilsexpedition/en/shipment)
    - [eShipper](https://ww2.eshipper.com/customer/shipping/quick-quote)
