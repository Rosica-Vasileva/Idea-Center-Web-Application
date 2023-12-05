## Test Case 1 (Home Page)
Users can access The Idea Center from its designated URL via the internet, which will load the Home page,
Carousel, and Navigation Pane, appropriate to the user's logged-in status  (unregistered/non-logged or
registered/logged).

## Registered/Logged users

## TC10: Verify NavBar Links  

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC1-10            |Users is logged in| Verify the NavBar links are displayed correctly. | 1.Log in the application.<br>2.Navigate to Home page.<br>3.Verify the presence of NavBar links:Home page,My profile,My ideas,Create idea, Logout. |All NavBar links are displayed as expected. | Pass           |

## TC11:Check carousel content   

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC1-11            |Users is logged in| Verify the the content of the carousel on the Home page. | 1.Log in the application.<br>2.Go to the Home page.<br>3.Check the content of the carousel slides. |Carousel slides should welcome the user and offer quick navigation options to their profile and ideas. | Pass           |

## TC12: Navigate to  "My profile"

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC1-12           |Users is logged in| Verify that the user can navigate to their profile from the Home page. | 1.Log in the application.<br>2.Go to the Home page.<br>3.Check on the ''My profile''link in the NavBar. |The user is redirected to their profil page. | Pass           |


## TC13: Navigate to  "My ideas"

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC1-13           |Users is logged in| Verify that the user can navigate to their ideas from the Home page. | 1.Log in the application.<br>2.Go to the Home page.<br>3.Check on the ''My ideas''link in the NavBar. |The user is redirected to a page displaying their ideas. | Pass           |

## TC14: Navigate to  Create idea

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC1-14           |Users is logged in| Verify the functionality to navigateto the "Create idea" page. | 1.Log in the application.<br>2.Go to the Home page.<br>3.Click on the "Create idea" link in the NavBar. |The user is redirected the page for creating a new idea. | Pass           |
