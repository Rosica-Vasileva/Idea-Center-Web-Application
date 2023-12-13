## 5. Test Case 5 (Idea Creation)
Logged users should be able to navigate to the Create Idea page, where they can create a New idea with a Title,
Picture (URL), and Description. After the idea creation process, users should be redirected to the My Ideas page,
where the newly created idea should be present.

This page can be accessed from the Navbar and contains fields for creating a new idea, including a Title (3-
70 characters length), Add picture field (picture is not uploaded, but must be a valid URL of a picture), and a
Describe your idea field (3-400 characters length). Title and Description are mandatory. After entering these details,
the user can click on the CREATE button to save the idea.

## TC1:Verify Access to "Create Idea" Page from Navbar.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC5-1            |The user is logged in.|Verify Access to "Create Idea" Page from Navbar. |1.Open the application.<br>2.Log in with valid credentials.<br>3.Navigate to the "Create Idea" page from the Navbar.|The system should allow the user to successfully access the "Create Idea" page from the Navbar.|Pass         |


## TC2: Navigate to "Create Idea" Page.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC5-1            |The application provides a navigation option to the "Create Idea" page.|Verify Navigation to "Create Idea" Page. | 1.Locate and click on the "Create Idea" link or button.<br>2.Observe the page that opens. |The system should allow the user to successfully navigate to the "Create Idea" page after logging in.|Pass         |

## TC3: Create a New Idea with Title,Picture (URL) and Description.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC5-2            |The application supports the creation of new ideas with a title, picture (URL), and description.|Verify Creation of a New Idea with Title, Picture (URL), and Description. |1.Open the application.<br>2.Log in with valid credentials.<br>3.Navigate to the "Create Idea" page.<br>4.Enter a title for the new idea.<br>5.Insert a valid picture URL for the idea.<br>6.Provide a description for the idea.<br>7.Click on the "Create Idea" button. |The system should successfully create a new idea with the specified title, picture (URL), and description.|Pass         |

## TC4:Redirect to "My Ideas" after Idea Creation.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC5-3            |The user has successfully created a new idea.|Verify Redirect to "My Ideas" after Idea Creation. | 1.Review the page to which the system redirects after creating an idea. |The user is successfully redirected to the "My Ideas"page,and the newly created ideas is displayed.|Pass         |



## TC5:Redirect to "My Ideas" after Idea Creation.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC5-5            |The user has navigated to the "Create Idea" page from the Navbar.|Verify Boundary Value Analysis (BVA) for Title and Describe Fields during Idea Creation. |1.Open the application.<br>2.Log in with valid credentials.<br>3.Navigate to the "Create Idea" page from the Navbar.<br>4.For the Title field:<br>a. Enter a title with 2 characters length.<br>b. Enter a title with 3 characters length.<br>c. Enter a title with 70 characters length.<br>d. Enter a title with 71 characters length.<br>For the Describe field:<br>a. Enter a description with 2 characters length.<br>b. Enter a description with 3 characters length.<br>c. Enter a description with 400 characters length.<br>d. Enter a description with 401 characters length.<br>Click on the "CREATE" button. |The user is successfully redirected to the "My Ideas"page,and the newly created ideas is displayed.|Pass         |




