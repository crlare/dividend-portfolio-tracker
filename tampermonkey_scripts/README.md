# All Information For Each Tampermonkey Script

This will provide some detailed information for each script in this directory.

## personal_capital_brokerage_holdings_getter.js

This script will run on the Personal Capital Website and place a green `Copy Holdings` button on
the `Holdings` tab of the brokerage account that you want to copy from. When the button is clicked,
the button will copy the holdings into JSON data to your clipboard which can then be pasted into
the GoogleSheets or any other program that wants to use the JSON data.

## etoro_holdings_getter.js

This script will run on etoro.com/portfolio and place a grey `Copy Holdings` button next to navbar buttons. 
When the button is clicked, the button will copy the holdings into JSON data to your clipboard which can then 
be pasted into the GoogleSheets or any other program that wants to use the JSON data.

###Known issues: 
- Currency won't always calculate correct price
- You'll not get holdings from people you're copying
