#### Title  
View filter clicking leads to a frontend crash

#### Severity  
Critical

#### Description  
A click on `View` option in Homepage leads to frontend crash, that leaves the page into 
a non-responsive state. 


#### How to Reproduce 
- Go to `https://academybugs.com/find-bugs/`  
- Click on any of the `View` view filter, e.g. `10`, or `50`  
- Observer the page behaviour

#### PoC  
![Video PoC](/assets/videos/UI_Crash.mp4)

#### Expected Result   
Frontend should filter the available number of product based on the clicked `View` filter number. 

