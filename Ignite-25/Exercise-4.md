## Exercise 4: Copilot Studio for Low-Code  (Optional)

In this exercise, you will use Microsoft Copilot Studio to build a low-code AI agent that connects to Azure Databricks as its knowledge source. The agent will answer business-related questions using live Databricks data. You’ll then publish the agent to Microsoft Teams, enabling users to interact with Databricks data seamlessly through natural language conversations.

### Task 4.1: Create an agent and connect Azure Databricks as its knowledge source to support Business Q&A.

1. Go to **[Copilot Studio](https://copilotstudio.microsoft.com/)**,  In the Welcome to Microsoft Copilot Studio page, select **Start free trial** and Proceed.

![](./media/copilottrail.png)

2. select **Agents** from the left menu, and click **+ New agent**.

![](./media/ex4t1i1.png)

> Note: Wait for page to load and refresh the page

3. On the **Start building your agent** page, click **Configure**, enter the following values in the respective fields and then click **Create**.

 **Agent name** : ``Databricks Agent``, 

**Description** : ``Responds to queries using data from your Databricks workspace``.

![](./media/ex4t1i2.png)

4. On the **Databricks Agent** page, scroll down and click **+ Add knowledge** to include a knowledge source.

![](./media/add.png)

5. On the **Add knowledge** page, click **Advanced**, then select **Azure Databricks**.

![](./media/ex4t1i4.png)

6. On the Select **Azure Databricks connection** pane, click on **Not connected** dropdown and select **Create new connection**.

 ![](./media/ex4iu.png)

6. In the Server Hostname field type: **adb-689745566023860.0.azuredatabricks.net**

7. In the HTTP path field type: **/sql/1.0/warehouses/30423e4b958bb27b** and click on **Create**.

![](./media/ex4t1i7.png)

9. In the pop-up window, select your account and click **Sign in**.

![](./media/ex4t1i8.png)

10. Select **zava_unity_catalog** and click **Select**.

![](./media/ex4t1i9.png)

11. Search for **schema-1957817.gold**, select the **gold_transactions** tables within it, and click **Add to Agent**.

![](./media/ex4t1i10i.png)

12. Paste the following question to **Test your agent**.

```
what is the percentage of fraudulent transactions in my dataset?
```

![](./media/ex4t1i10ii.png)

13. If a prompt appears asking for permission to connect in order to continue, please click **Allow**.

![](./media/ex4allow.png)

14. If Agent responded with:
 **Let's get you connected first, and then I can find that info for you. ​Open connection manager​ to verify your credentials.**
 Click on **​Open connection manager**.

![](./media/ex4t1i13.png)

>**Note**:  If prompted to sign in, use your user ID to complete the sign-in process.

![](./media/ex4t1i14.png)

15. Click on **Connect**.

![](./media/ex4t1i15.png)

16. Click on **Submit**.

![](./media/ex4t1i16.png)

17. Navigate back to the **Agent** page and Paste the same question again into **Test your agent**.

```
what is the percentage of fraudulent transactions in my dataset?
```

![](./media/ex4t1i10ii.png)

### Task 4.2: Publish the agent in Microsoft Teams channels and make it accessible to users.

1. Click on **Channels**, then click on **Microsoft Channels**.

![](./media/teams1.png)

2. Navigate to following url to see the agent in action : [Click by click](https://click-by-click.azurewebsites.net/#preview/mhw2w6exgz21zno97ch)

Congratulations! As Data Engineers and Data Analysts, you have empowered Zava to transform its disparate data sources into actionable insights-driving growth, enhancing customer satisfaction, and securing a competitive edge.

