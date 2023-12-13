## Test Case 1 (Home Page)
Users can access The Idea Center from its designated URL via the internet, which will load the Home page,
Carousel, and Navigation Pane, appropriate to the user's logged-in status  (unregistered/non-logged or
registered/logged).

## Registered/Logged users

## TC9: Verify NavBar Links for Registered Users.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC1-9            |Users is logged in.| Verify the NavBar links are displayed correctly. | 1.Log in the application.<br>2.Navigate to Home page.<br>3.Verify the presence of NavBar links:Home page,My profile,My ideas,Create idea, Logout. |All NavBar links are displayed as expected. | Pass           |

## TC10:Check carousel content  for Registered Users.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC1-10            |Users is logged in.| Verify the the content of the carousel on the Home page. | 1.Log in the application.<br>2.Go to the Home page.<br>3.Check the content of the carousel slides. |Carousel slides should welcome the user and offer quick navigation options to their profile and ideas. | Pass           |

## TC11: Navigate to  "My profile"  for Registered Users.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC1-11           |Users is logged in.| Verify that the user can navigate to their profile from the Home page. | 1.Log in the application.<br>2.Go to the Home page.<br>3.Check on the ''My profile''link in the NavBar. |The user is redirected to their profil page. | Pass           |


## TC12: Navigate to  "My Ideas"  for Registered Users.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC1-12          |Users is logged in.| Verify that the user can navigate to their ideas from the Home page. | 1.Log in the application.<br>2.Go to the Home page.<br>3.Check on the ''My ideas''link in the NavBar. |The user is redirected to a page displaying their ideas. | Pass           |

## TC13: Navigate to  Create idea  for Registered Users.

| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC1-13           |Users is logged in.| Verify the functionality to navigateto the "Create idea" page. | 1.Log in the application.<br>2.Go to the Home page.<br>3.Click on the "Create idea" link in the NavBar. |The user is redirected the page for creating a new idea. | Pass           |

## TC14: Logout functionality  for Registered Users.
| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC1-14          |Users is logged in.| Verify the functionality of the Logout button. | 1.Log in the application.<br>2.Go to the Home page.<br>3.Click on the Logout button in the NavBar. |The user is logged out,and they are redirected to the login page . | Pass           |

## TC15: Verify Quick Navigation Buttons in Carousel  for Registered Users.
| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC1-15          |Users is logged in.|Check if the buttons in the carousel slides provide quick navigation <br>to "My profile" and "My ideas". | 1.Log in to the system.<br>2.Go to the Home page with the carousel.<br>3.Review the slides in the carousel and check for the presence of buttons for "See your profile" and "See your ideas".<br>4.Click on the "See your profile" button.<br>5.Navigate back to the Home page with the carousel<br>6.Click on the "See your idea"button. |The users is redirected to their profile page,the users is redirected to the page displaying their ideas. | Pass           |
