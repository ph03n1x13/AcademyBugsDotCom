#### Title
Currency selection in `SELECT A CURRENCY` dropdown does not work as expected

#### Severity
High

#### Description
When a user selects an expected currency from he `SELECT A CURRENCY` dropdown, the currency
remains USD `$` in the frontend

#### How to Reproduce
- Go to `https://academybugs.com/find-bugs/`  
- Select a product  
- User is redirected to `https://academybugs.com/store/<product>`  
- Select a currency from `SELECT A CURRENCY` e.g. `GBP`  
- Observe the Price currency  

#### PoC
[Video PoC](/assets/videos/Currency_Crash.mp4)

#### Expected Result
The currency value should be changed and converted to USD market price as per the selected currency from the dropdown.
