# Netsuite Developer Asessment
The goal of this assessment is to test knowledge of json data structures and  programming concepts. The take home assignment should not take longer than an hour, but feel free to take 3 days to complete if you have a busy schedule. 

# Instructions
<ol>
  <li>Please clone the repo or download the files inside the repo</li>
  <li>In the language of your choice, preferably in Javascript, please open or copy and paste the JSON object in the file `order.json`. Please create functions or classes that meet the following criteria: </li>
  <ol>
    <li>It takes in the `order.json` object and returns a related Item Fulfillment object. It should return all the relevant line_items within the line_items array. The `order.json` file should have all of the information that you need.</li>
    <li>The number of line items should be equal to the length of the line_items array in order.json</li>
    <li>Here's an example of what the IF object and keys should look like the following example (will not look entirely like this):</li>
     
      ```
      {
        "fulfillment": {
          "id": "your_auto_generated_fulfillment_id",
          "order_id": "referencing the id in order.json",
          "shipping_address": {
            "first_name": "Test",
            "address1": "2325 3rd Street STE 410",
            "phone": null,
            "city": "San Francisco",
            "zip": "94107",
            "province": "California",
            "country": "United States",
            "last_name": "Test",
            "address2": "",
            "company": "",
            "latitude": 37.7598342,
            "longitude": -122.3879013,
            "name": "Test Test",
            "country_code": "US",
            "province_code": "CA"
          },
          "line_items": [
            "sku": "example_sku",
            "quantity: "example_quantity"
          ]

        }
      }
      ```

    
 
    
  </ol>
  <li>Structure the functions/class however you like, but be prepared to defend your design decisions</li>
  <li>Feel free to write tests</li>
  <li>Send over the link to your Github repo with your solutions. Please give instructions on how to run your functions. You can also email a zip file with instructions.</li>
  <li>We will go over the design of your functions in the interview</li>
  <li>Please reach out to Booth and Partners if you have any questions</li>

</ol>
