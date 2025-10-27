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

<div class="description">
  <h2 style="color: #333;">📄 Description</h2>
  <p>
    <br> 
    This demo shows how Zava Financial, a fictious company transformed its operations using Azure Databricks to address critical KPIs across banking and insurance. The team deployed AI-powered accelerators for credit decisioning, smart claims processing, and fraud detection, improving net interest margin, reducing turnaround time, and increasing fraud detection rates. Using Lakehouse architecture, Lakeflow Connect, and Unity Catalog, they unified data engineering, ML, and BI with strong governance. Business users accessed insights via AI/BI Genie, integrated with Copilot Studio and Teams for conversational analytics and workflow automation to get quick real-time insights. Security was enhanced through AIM, ensuring seamless identity management via Microsoft Entra ID.
  </p>
</div>

<div class="highlight-box">
  <strong>IMPORTANT:</strong><br>
  Please launch the demo <strong>15 minutes before presenting</strong>. Resources may take a few minutes to provision.<br>
  ODL access provisioning may take <strong>5–7 minutes</strong>.<br>
  If unauthorized errors occur, wait a few minutes and then press <strong>Ctrl + Shift + R</strong> to refresh.<br>
  Databricks may take around <strong>30–40 minutes</strong> to become available to the ODL user. This is due to Databricks default behavior of syncing users every 40 minutes.<br>
 For Microsoft Fabric, once you login with the ODL user, please wait <strong>5 minutes</strong> and refresh the screen to see the Workspaces.
</div>

<!-- Auth Table -->

| **User Login Credentials** |                                       |
|-----------------|---------------------------------------|
| Username    | <inject key="AzureAdUserEmail" />     |
| Password   | <inject key="AzureAdUserPassword" />  |
| Teams Login Username | <inject key="Teams Login UserName" /> |
| Teams Login Password | <inject key="Teams Login Password" /> |


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
      <td>Demo Web App</td>
      <td>
        <a href="https://app-azuredatabricksdemo.azurewebsites.net/" target="_blank">
          https://app-azuredatabricksdemo.azurewebsites.net/
        </a>
      </td>
    <tr>
    <td>Azure Databricks Service</td>
    <td>
      <a href="https://adb-1182786345533470.10.azuredatabricks.net/" target="_blank">
        https://adb-1182786345533470.10.azuredatabricks.net/
      </a>
    </td>
    </tr>
  </tbody>
</table>




