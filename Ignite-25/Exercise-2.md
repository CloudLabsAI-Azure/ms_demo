## Exercise 2: AI-Driven Insights with Azure AI Foundry & Genie

In this exercise, you will integrate Azure Databricks Genie with Azure AI Foundry to enable AI-driven insights and natural language interaction with your data. You’ll create a Genie assistant to analyze transactions and detect fraud patterns, connect it to AI Foundry for seamless orchestration, and finally use the AI agent within a custom web application to deliver interactive, data-powered intelligence.

### Task 2.1: Create a Databricks Assistant AI/BI Genie

 In this Task You’ll create a Genie assistant to analyze transactions and detect fraud patterns

1. In the left menu bar, click on **Genie**.

![databricks](./media/databricks3.png)

2. Click on **+ New**.

![databricks](./media/databricks4.png)

3. Click on **All** and then click on **zava_unity_catalog**.

4. Click on the **schema-1957817** you created.

5. Select **gold_transactions**, then click on **Create**.

![databricks](./media/databricks7.png)

6. Click on **New Space** in the top left to edit the name and replace it with **Zava_Genie**.

![databricks](./media/databricks9.png)

7. Paste the following question in chat box and click on send.

   ```
   Are there any fraud hotspots based on geo-location?
   ```


![databricks](./media/genie1.png)

8. Observe the response from Genie, then click **Show code** to view the code Genie used to formulate the answer.

   > **Note**: The responses from Genie may not match the ones in the screenshot but will provide a similar response.

    ![databricks](./media/genie2.png)


### Task 2.2: Connect AI/BI Genie inside AI Foundry.

In this Task You’ll connect AI/BI Genie to AI Foundry for seamless orchestration

1. Click on the following link to open the **AI Foundry portal**: [AI Foundry link](https://ai.azure.com/foundryResource/overview?wsid=/subscriptions/2afb8c66-936c-466c-8c6d-c69b42ec2e95/resourceGroups/rg-ignite-25-qnyueas/providers/Microsoft.CognitiveServices/accounts/AIhub-qnyueas&tid=f94768c8-8714-4abe-8e2d-37a64b18216a)

2. Scroll down and then click on **Management center**.

   ![databricks](./media/aifoundary3.png)

3. Click on **Connected resources**, then click on **+ New connection**.

   ![databricks](./media/aifoundary4.png)

4. Scroll down and click on **Azure Databricks**.

   ![databricks](./media/aifoundary5.png)

5. Click the dropdown for **Connection Type**, then Select **Genie**.

   >**Note**: Please make sure you select the **Resource group** you opened in **step 1**.

    ![databricks](./media/aifoundary6.png)

7. Click the drop down for **Select Genie space**, choose **Zava_genie**, and then click on **Add connection**.

   ![databricks](./media/aifoundary7.png)

8. Once it's **Connected**, Click on **close**.

   ![databricks](./media/aifoundary8.png)

### Task 2.3: Use Agent Created Inside AI Foundry with Custom Web App

In this Task, You'll use the AI agent within a custom web application to deliver interactive, data-powered intelligence.


1. Open the webapp **https://app-aifoundry-genieintegration.azurewebsites.net/#/landing-page**

2. Click on the robot icon located at the bottom-right corner of the page.

   ![](./media/customwebapp1.png)

3. Click on the first pre-populated question.

   ![](./media/customwebapp2.png)

4. Observe the response.

   ![](./media/customwebapp3.png)

5. Click on the second pre-populated question and observe the response.

   ![](./media/customwebapp4.png)

6. Click on the third pre-populated question and observe the response.

   ![](./media/customwebapp5.png)

7. Click on the next pre-populated question and observe the response.

   ![](./media/customwebapp6.png)

