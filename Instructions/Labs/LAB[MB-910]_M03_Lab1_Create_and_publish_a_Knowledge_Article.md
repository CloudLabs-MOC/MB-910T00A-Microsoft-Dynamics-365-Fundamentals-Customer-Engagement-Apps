## Module 3: Learn the Fundamentals of Dynamics 365 Customer Service

## Practice Lab 3.1 - Create and publish a Knowlege Article in Dynamics 365 Customer Service

  - **Estimated Time**: 15 minutes

## Setup the lab environment

1. Open the browser in your virtual machine and navigate and login to https://admin.powerplatform.microsoft.com/ using the credentials given in lab environment details tab.

    ![](../images/intro-1.png)

2. Create a new environment by clicking on **+ New**

    ![](../images/module4/lab1/setup/1.png)
    
3. On the Window that opens in the right, Enter first a unique name for the environment like **customer-deploymentID** and select **Sandbox** as type and Set **Yes** for create a database for this environment and then click **Next**.

    ![](../images/module3/setup/1.png)
    
4. Scroll down and select **Enable Dynamics 365 apps** to **Yes** and inautomatically deploy these apps , select **Customer Service Pro**.

    ![](../images/module3/setup/2.png)

5. Just ensure the settings as in the image below and select **Save**.

    ![](../images/module3/setup/3.png)

6. A field will appear under environemnts with name customer and it will be in preparing state and once the environment is ready, select the environment and find and click the URL to open the Customer Service Hub application.

    ![](../images/module3/setup/4.png)
    
    ![](../images/module3/setup/5.png)
    
    ![](../images/module3/setup/6.png)
 
7. The apps section will appear and from the list select **Customer Service Hub**.

    ![](../images/module3/setup/7.png)
    
8. We will be now in the customer service hub and let it be open to perform the remaining exercises.

## Instructions

1. If is not open already, open the **Dynamics 365 Customer Service Hub** application. 

2. Using the navigation on the left side of the screen, select **Knowledge Articles**.

3. To easily see the which articles are in different stages, select the drop-down arrow next to **My Active Articles**.

    ![](../images/module3/lab1/4.png)

4. Select the **Draft Articles** view.

    ![](../images/module3/lab1/5.png)

5. Select **Approved Articles**.

    ![](../images/module3/lab1/6.png)

6. Switch back to **My Active Articles**

7. On the **Command Bar**, select the **New** button.

    ![](../images/module3/lab1/7.png)

8. After the new record opens, select the drop-down arrow next to the **Status reason** field in the record header at the top. Set **Language** to **English - United States**.

    ![](../images/module3/lab1/8.png)

8. Complete the article as follows:

	- **Title:** Item Broken on Arrival –[DeploymentID]

	- **Keywords:** Broken Item, Damaged, Return

	- **Description:** Helps resolve issues when an Item arrives damaged. 

    ![](../images/module3/lab1/9.png)
    
9. Enter the following text into the Content Designer text.   
‎  
‎	Item Arrived Damaged

	When an item arrives damaged, do the following:

	1. Open our web portal

	2. Locate your order record

	3. Select return Item

	4. Select damaged for the reason

	5. Select Print

Once we have received the returned / damaged item, your account will be credited back the amount.

**NOTE:** You can add formatting to the text if desired. 

   ![](../images/module3/lab1/10.png)

10. On the **Command Bar**, select the **Save** button to save the Knowledge Article and leave it open.

   ![](../images/module3/lab1/11.png)

11. On the **New Process**, select the **Author** stage, set the **Article Subject** field to **Delivery** (Located under Service). 

12. Set the **Mark for Review** field to **Completed**.

13. Select **Next Stage** button to advance to **Review** stage.

   ![](../images/module3/lab1/12.png)

14. On the **Command Bar**, select the **Save and Close** button to save your changes and close the article.

   ![](../images/module3/lab1/13.png)

After the author initially creates the record, it will generally go through an approval process before it is live. Next, we will act as an approver and approve the article. 

15. In the Knowledge Articles, switch the view to **Proposed Articles** to see which articles need your approval.

   ![](../images/module3/lab1/14.png)

16. Open the **Item Broken on Arrival –[DeploymentID]** article you just created.

   ![](../images/module3/lab1/15.png)

17. On the **New Process**, select the **Review** stage. Set the **Review** field to **Approved**.

   ![](../images/module3/lab1/16.png)

18. You will be asked to confirm the article approval, select **OK**. 

   ![](../images/module3/lab1/17.png)

19. Select the **Next Stage** button to advance to the **Publish** stage. 

   ![](../images/module3/lab1/18.png)

20. On the **Command Bar** at the top of the article, select the **vertical ellipsis** at the left of the command bar. From the menu that appears, select **Relate Product**.  

21. On the **New Process**, select the **Publish** stage. 

   ![](../images/module3/lab1/20.png)

22. Mark the **Set Product Associations** as **Complete**. 

23. Set the **Expiration Date** to **one year from today at 12:00 AM**. 

24. Select the **Finish** button to complete the process. 

   ![](../images/module3/lab1/21.png)

25. On the **Command Bar** for the article, select the **Publish** button. 

   ![](../images/module3/lab1/22.png)

26. Confirm that the following is selected:

	- **Publish:** Now

	- **Published Status:** Published

	- **Expiration Date:** One year from today at 12:00 AM

	- **Expiration State:** Expired

	- **Expiration Status:** Expired

	- **Publish Approved translations:** No

   ![](../images/module3/lab1/23.png)
