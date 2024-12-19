# Module 4: Explore Dynamics 365 Sales

## Objectives

In this module, you will manually be creating a lead for Jane Anderson. Jane works for a company called Jim works for a company called **ABC Consulting**. Not only will you be capturing the lead information in the system, but you will be leveraging the tools available in Dynamics 365 Sales to qualify the lead as an opportunity and work it through closing the opportunity.

## Estimated Time: 60 minutes

## Architecture Diagram

   ![](./media/mod3.png)

## Task 1: Create and manage an opportunity in Dynamics 365 Sales 

1. Click on **Customer Insights - Journeys** from the top left corner and from the list of apps open the **Sales Hub**.

   ![](./media/pp290.png)

   ![](./media/pp291.png)

1. In the **Dynamics 365 Sales Hub** application from the left navigation pane, select **Leads**.

   ![](./media/pp29.png)

1. On the **My Open Leads** view, click on the ellipsis and select the **+ New** button to create a new lead.

   ![](./media/pp30.png)

1. Complete the **Lead** information as follows:

	- **Topic:** Wants to upgrade their existing equipment 

	- **First Name:** Jane

	- **Last Name:** Anderson 

	- **Job Title:** CEO

	- **Business Phone:** 888-555-6767

	- **Email:** JaneA<inject key="DeploymentID" enableCopy="false" />@sample.com

	- **Company:** ABC Consulting 

	- **Street 1:** 1987 191st Ave N

	- **City:** Fargo

	- **State/Province:** ND

	- **Zip/Postal Code:** 58102

1. Select the **Save** button to save the Lead and leave it open.

   ![](./media/pp31.png)

1. On the **Lead to Opportunity** sales process, select the **Qualify** stage.

   ![](./media/pp32.png)

1. Complete as follows:

	- **Purchase Timeframe:** Immediate

	- **Estimated Budget:** $50,000

	- **Purchase Process:** Committee

1. Close the **Qualify** stage fly-out and click on **Save**

   ![](./media/pp33.png)

   ![](./media/pp34.png)

1. On the **Command bar**, select the **Qualify** button.

    ![](./media/pp35.png)
 
     > **Note:** If you do not see the Qualify button, select the **More Commands** button (Looks like three vertical dots).

1. The system will close the **Lead** record and create a new **Opportunity** record. Notice that the **Lead to Opportunity** business process flow has automatically been advanced to the **Develop** stage.

1. On the **Opportunity Header** at the top of the record, select the down arrow next to the **Owner** field.

    ![](./media/pp3610.png)

1. Complete as follows:

   - **Est. Close Date:** Two days from today

   - **Est Revenue:** $50,000

        ![](./media/pp37.png)

1. In the **Stakeholders** sub-grid, notice that **Jane Anderson** is already defined as a stakeholder.

    ![](./media/pp38.png)

1. On the **Sales Team** sub-grid, select the **Vertical Ellipsis**. From the menu that appears select **+ New Connection**.

   ![](./media/pp39.png)

1. Search for and choose your user record. Once completed, select the **Add** button.

   ![](./media/pp40.png)

1. On the **Competitors** sub-grid, select the **Vertical Ellipsis** (look like three vertical dots). From the menu that appears select **Add Existing Competitor**.

   ![](./media/pp41.png)

1. On the **Lookup Record** screen, select **+ New Record**, and then select **Competitors**.

1. On the **Quick Create: Competitor** form, set the **Name** field to **Coho Technologies**

1. Select the **Save and Close** button.

   ![](./media/pp42.png)

1. **Coho Technologies** should be selected in the lookup record window. Click the **Add** button to finish adding the competitor.

   ![](./media/pp43.png)

	>**Congratulations** on completing the task! Now, it's time to validate it. Here are the steps:
	
	 > - Click the Lab Validation tab located at the upper right corner of the lab guide section and navigate to the Lab Validation tab.
	 > - Hit the Validate button for the corresponding task.
	 > - If you receive a success message, you can proceed to the next task. If not, carefully read the error message and retry the step, following the instructions in the lab guide.
	 > - If you need any assistance, please contact us at labs-support@spektrasystems.com. We are available 24/7 to help you out.
	
	<validation step="e642cac3-71d8-4e18-bd24-30c694802a39" />

21. On the **Lead to Opportunity** business process flow, select the **Develop** stage.

22. Complete as follows and select the **Next Stage** button to advance to the **Propose** stage.

	- **Identify Stakeholders**: completed

	- **Identify Competitors**: completed

         ![](./media/pp44.png)

23. On the **Propose** stage, mark all four tasks as **completed**. Select **Next Stage**.

    ![](./media/pp45.png)

24. On the **Close** stage, mark all tasks as **completed**.

   ![](./media/pp46.png)

25. Select the **Finish** button on the business process flow.

26. Now that you have completed the business process, you need to close the opportunity.

27. On the **Command Bar** of the opportunity, select the **Close as won** button.

    ![](./media/pp47.png)

28. On the **Close Opportunity** dialog, select the **OK** button to finish closing the opportunity record.

## Review

In this module we have demonstrated proficiency in utilizing tools within Dynamics 365 Sales to progress leads through stages, from initial capture to opportunity closure, effectively optimizing sales workflows.

## You have successfully completed this module.Click Next
