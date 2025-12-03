<style>
  table {
    width: 80%;
    margin: 30px auto;
    border-collapse: collapse;
    font-family: 'Segoe UI', sans-serif;
    font-size: 15px;
  }

  th {
    background: #f2f2f2;
    padding: 10px;
    text-align: left;
    border: 1px solid #ddd;
  }

  td {
    width: 900px;
    height: 10px;
    padding: 10px;
    text-align: left;
    border: 1px solid #ddd;
  }

  .description {
    margin: 0 auto;
    font-family: 'Segoe UI', sans-serif;
    font-size: 14px;
    color: #444;
  }

  .highlight-box {
    background: #f8f9fa;
    padding: 12px 24px 12px 32px; /* Top, Right, Bottom, Left */
    border-left: 4px solid #0078d4;
    margin: 20px auto;
    font-size: 14px;
    text-align: left;
}

</style>


<!-- Auth Table -->

| **User Login Credentials** |                                       |
|-----------------|---------------------------------------|
| Username    | <inject key="AzureAdUserEmail" />     |
| Password   | <inject key="AzureAdUserPassword" />  |


<!-- Resource Details Table -->
<table>
  <thead>
    <tr>
      <th>Resources</th>
      <th>Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>Azure Databricks</td>
    <td>
        <a href="https://adb-486601822035519.19.azuredatabricks.net/" target="_blank">
          https://adb-486601822035519.19.azuredatabricks.net/
        </a>
    </td>
    </tr>
    <tr>
    <td>Microsoft Fabric Workspace</td>
    <td>
        <a href="https://app.fabric.microsoft.com/home" target="_blank">
          https://app.fabric.microsoft.com/home
        </a>
    </td>
    </tr>
  </tbody>
</table>

## Getting Started with Lab

1. Open an InPrivate browsing window and paste the CloudLabs link.

2. In the new window, navigate to **https://portal.azure.com**.

3. On the Microsoft Azure browser tab, paste the provided Username:**<inject key="AzureAdUserEmail" />** to Sign in and click **Next** 

   ![](./media/gs3.png)

4. Now paste the following Password:**<inject key="AzureAdUserPassword" />** and click on Sign in.

   ![](./media/gs4.png)

5. Search for **Azure Databricks** and select it.

   ![](./media/gs5.png)


6. Click on the **adb-fabric-9msyp2f** from the result.

   ![](./media/gs6.png)

7. Scroll down and select **Launch Workspace** to open the Databricks workspace.

   ![](./media/gs7.png)

8. Click on **Continue with Microsoft Entra ID**.

   ![](./media/gs2.png)

   > **Note:** If you encounter any permission-related issues, please refresh the page 2-3 times. The page should load correctly afterward.

9. Now, click on Next from the lower right corner to move on to the next page.

   ![](./media/step1.png)


