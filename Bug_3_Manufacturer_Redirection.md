#### Title  
A click on `Manufacturer` link lands in an inappropriate 404 not found page

#### Severity
Medium 

#### Description
Title is self-explanatory 

#### How to Reproduce
- Go to `https://academybugs.com/find-bugs/`
- Open a product 
- Click the link on the `Manufacturer` label 
- Observe the redirection  

#### PoC 
![Video PoC](assets/videos/Page_Redirection.mp4)

#### Expected Result
1. A user should be shown the products produced by a manufacturer 
2. If no products of the manufacturer is found, user should be shown an appropiate 
error message like `Sorry, no products of <Manufacturer> found!`