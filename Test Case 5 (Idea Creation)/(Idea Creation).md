## 5. Use Case 5 (Idea Creation)
Logged users should be able to navigate to the Create Idea page, where they can create a New idea with a Title,
Picture (URL), and Description. After the idea creation process, users should be redirected to the My Ideas page,
where the newly created idea should be present.

## TC1: Navigate to Create Idea Page.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC5-1            |Registered user|Navigate to Create Idea Page. | 1.Locate and click on the Create Idea link or button.<br>2.Observe the page that opens. |The user is successfully redirected to their Create Idea pgae.|Pass         |

## TC2: Create a New Idea with Title,Picture (URL) and Description.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC5-2            |The user is on the Create Idea page|Users should be able to successfully create a new idea with a title,picture(URL) and description. | 1.Enter a title for the idea.<br>2.Enter a valid URL for the picture.<br>3.Enter a description for the idea.<br>4.Save the idea. |The idea is created successfully and the user is redirected to the "My ideas" page.|Pass         |

## TC3:Redirect to "My Ideas" after Idea Creation.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC5-3            |The user has successfully created an idea.|The user is successfully redirected to the "My Ideas" page. | 1.Review the page to which the system redirects after creating an idea. |The user is successfully redirected to the "My Ideas"page,and the newly created ideas is displayed.|Pass         |



## TC4:View Created Idea.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC5-4            |The user has successfully created an idea.|Users who have created a new ideas should be able to successfully view it. | 1.Locate the idea in the "My ideas" list.<br>2.Click on the "View" button for the created idea. |The idea is successfully viewed and the user sees the information entered during its creation.|Pass         |


## TC5:Edit Create Idea.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC5-5            |The user has successfully created an idea.|Users who have created a new ideas should be able to successfully edit it. | 1.Locate the idea in the "My ideas" list.<br>2.Click on the "Edit" button for the created idea.<br>3.Edit the information of the idea.<br>4.Save the changes. |Changes to the idea's information are successfully saved.|Pass         |


## TC6: Delete Created Idea.


| **Test Case ID** | **Prequisites** | **Title/Description** | **Steps** | **Expected Result** | **Pass/Fail** |
|------------------|-----------------|------------------------|-----------|----------------------|---------------|
| TC5-6            |The user has successfully created an idea.|Users who have created a new ideas should be able to successfully delete it. | 1.Locate the idea in the "My ideas" list.<br>2.Click on the "Delete" button for the created idea.<br>3.Confirm the deletion of the idea.|The idea is successfully deleted and is no longer visible in the "My Ideas" list.|Pass         |
