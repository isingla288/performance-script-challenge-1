#Performance-Challenge-1

A testing challenge to be solved as part of a screening process

#Context
1. You are the quality performance engineer for a team at Bunnings.
2. You are retrofitting some testing procedures on the now live website. https://www.bunnings.com.au 

#Challenge

1. You are to script a test case and create a scenario for the newly rolled out "Add an item to cart" feature on this site, the feature in question is outlined in below steps.
2. Write test performance test scripts for this use case using GATLING
3. The expectation is that using this script, I should be able to get performance stats when I search any term (e.g. drills, paint, etc) and add the first item to the cart.
4. Use scripting best practices including naming conventions, assertions and comments

#Deliverables

1. Spend as little or as much time as you like on the challenge, please record the total time you spend on this and include it in your response (Suggested time: 2 hours)
2. The script should work in Gatling version 3.3.1
3. If you complete the scripting challenge, the scripts, data files, scenario and result log files must be committed back into a Public Repo(created by you) in Github and the URL shared back for review.

#Use Case Steps
1. Step 1: Hit the homepage on this site https://www.bunnings.com.au 
2. Step 2: Search for a term "Hammers" in the search bar (Ensure you wait for AJAX calls to compelete as you type 1 alphabet at a time)
3. Step 3: Identify the first item displayed into the search results and add this item into the cart by clicking on to "Add to cart" icon button
4. Step 4: Once an item added, click on to "Review and checkout" button displayed on the screen
5. Step 5: Now, you can view the previously selected item under "Review Cart" section.
6. Step 6: Click on "-" sign in product quantity and then click on "remove". You should get "Your cart is empty"
7. Step 7: Click on Top banner with "Bunnings" on it
8. Step 8: On this page, in the "Explore our range of products for spring" section select the **third item**

This is the end of use case. In case of any doubts use your best judgement and document assumptions made.
