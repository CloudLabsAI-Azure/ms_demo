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
    <br> This demo showcases how Zava built a secure and governed data estate using Microsoft Purview and Microsoft Fabric. Data is cataloged and organized into governance domains and data products to enable enterprise-wide discovery, lineage, and metadata management. Purview’s data quality, glossary, and governance reports help monitor data health and maintain compliance across the organization. Security is enforced through Data Loss Prevention policies, sensitivity labels, and fine-grained access controls such as Row-Level, Column-Level, and Object-Level Security in Fabric. Additionally, Microsoft Defender for Cloud and DSPM for AI provide continuous threat monitoring and AI data protection across Zava’s cloud environment.
  </p>
</div>

<div class="highlight-box">
  <strong>IMPORTANT:</strong><br>
  Please launch the demo <strong>15 minutes before presenting</strong>. Resources may take a few minutes to provision.<br>
  ODL access provisioning may take <strong>5–7 minutes</strong>.<br>
  If unauthorized errors occur, wait a few minutes and then press <strong>Ctrl + Shift + R</strong> to refresh.<br>
  For Microsoft Fabric, once you login with the ODL user, please wait <strong>5 minutes</strong> and refresh the screen to see the Workspaces.<br>
  <span style="color:red; font-weight:bold;">Note:</span>
  If you face any issues while accessing the demo environment, please reach out to
  <a href="mailto:mdxazuredemosupport@spektrasystems.com">mdxazuredemosupport@spektrasystems.com</a>
  and include the ODL username displayed in your lab environment details for faster assistance.
</div>

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
    <td>Azure Cosmos DB account</td>
    <td>
      <a href="https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.DocumentDb/databaseAccounts/cosmosdb-herodemo-001/overview" target="_blank">
        https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.DocumentDb/databaseAccounts/cosmosdb-herodemo-001/overview
      </a>
    </td>
    </tr>
    <tr>
    <td>Microsoft Purview</td>
    <td>
      <a href="https://purview.microsoft.com/home?tid=f94768c8-8714-4abe-8e2d-37a64b18216a" target="_blank">
        https://purview.microsoft.com/home?tid=f94768c8-8714-4abe-8e2d-37a64b18216a
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



