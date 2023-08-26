## Meet

## Scenarios 1: Successful User Registration
Given the user is on the registration page
When they fill in the required information and click the "Register" button
Then they should see a success message and receive a confirmation email

## Scenarios 2: User Registration with Existing Email
Given the user is on the registration user with the same email
When they fill in the required information and click the "Register" button   
Then they should see an error message indicating the email is already in use

## Scenarios 3: User Login
Given the user is on the login page
When they enter their valid credentials
Then they should be redirected to their dasboard

## Scenarios 4: Creating a Post
Given the user is logged in 
When they navigate to the "Create Post" page and write a post and click the "Publish" button
Then the post should appear on the main feed

## Scenarios 5: Successful Search
Given the user is on the main feed
When they enter a search query in the search bar and click the "Search" button 
Then they should see a list of posts related to the search query

