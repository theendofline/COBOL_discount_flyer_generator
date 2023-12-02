# COBOL_with_HTML_discount_flyer_generator

## Overview
This COBOL program, `JSONCBL`, processes grocery store inventory data from a JSON file to generate a flyer with discounted prices for items nearing their expiry date. It's designed to help stores quickly advertise sales on perishable goods.

## Features
- **JSON Parsing**: Reads inventory data in JSON format.
- **Flyer Generation**: Automatically creates a flyer with discounted items.
- **Dynamic Pricing**: Calculates 50% discounts for items close to expiry.

## Installation and Setup
1. Clone the repository: `git clone [repository-url]`
2. Ensure you have the COBOL compiler installed.
3. Compile the COBOL program using the provided JCL script.

## Usage
- Run the program using the command: `[command to run the program]`
- Provide the JSON file as specified in the JCL.
- The output will be a flyer in either TEXT or HTML format, based on the provided parameter.

```html
<html><head><style>body{font-family:IBM Plex Sans;background:#98CEF4;color:black;}img{width:250px;}table{margin-left:auto;margin-right:auto;border:1px solid black;width:250px;background:white;}#title{text-align:center;font-family:IBM Plex Sans;}.price{color:green;font-size:50px;}.discount{color:red;font-size:20px;}.product{font-size:15px;}#footer{text-align:center;font-size:larger;}</style></head><body><div id="title"><h1>Corner Grocery Store</h1>

</div><table><tr><td colspan=2><img src="https://ibmzxplore-static.s3.eu-gb.cloud-object-storage.appdomain.cloud/AdobeStock_65310327.jpeg"></td></tr> <tr><td class="price">$0.44</td><td><span class="discount">Save $0.45</span><br><span class="product">Canned Tuna <br>Was: $0.89</span></td></tr></table><br>

</div><table><tr><td colspan=2><img src="https://ibmzxplore-static.s3.eu-gb.cloud-object-storage.appdomain.cloud/AdobeStock_62625977.jpeg"></td></tr> <tr><td class="price">$0.24</td><td><span class="discount">Save $0.25</span><br><span class="product">Green Beans <br>Was: $0.49</span></td></tr></table><br>

</div><table><tr><td colspan=2><img src="https://ibmzxplore-static.s3.eu-gb.cloud-object-storage.appdomain.cloud/AdobeStock_282479225.jpeg"></td></tr> <tr><td class="price">$1.99</td><td><span class="discount">Save $2.00</span><br><span class="product">Peanut butter <br>Was: $3.99</span></td></tr></table><br>

<div id="footer"><p>

Flyer in effect 2021-09-18 to 2021-09-25

</p></div></body></html>
```

## Contributing
Contributions to the project are welcome! Please refer to the contributing guidelines for more information.

## License
This project is licensed under the [MIT License](LICENSE).

