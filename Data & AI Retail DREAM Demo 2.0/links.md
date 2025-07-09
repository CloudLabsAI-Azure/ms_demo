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


  }
</style>

<div class="description">
  <h2 style="color: #333;">📄 Description</h2>
  <p>
    This demo showcases the power of Azure Synapse Analytics, Azure Purview, Cosmos DB with Azure Synapse Link, Power BI, AI/ML, Power Apps and Azure Data Explorer. The core focus is to demonstrate how our data and AI can empower retail sector organizations to improve customer insights, enhance customer experience and improve operational efficiency.
  </p>
</div>

<div class="highlight-box">
  <strong>IMPORTANT:</strong><br>
  Please launch the demo <strong>15 minutes before presenting</strong>. Resources may take a few minutes to provision.<br>
  ODL access provisioning may take <strong>5–7 minutes</strong>.<br>
  If unauthorized errors occur, wait a few minutes and then press <strong>Ctrl + Shift + R</strong> to refresh.
</div>

<!-- Auth Table -->

| **User Login Credentials** |                                       |
|-----------------|---------------------------------------|
| Username    | <inject key="AzureAdUserEmail" />     |
| Password   | <inject key="AzureAdUserPassword" />  |

| **Ai Resources Login Credentials** |                                       |
|-----------------|---------------------------------------|
| Ai Resources Username    | retail-ai-reader-user@cloudlabsai.ms     |
| Ai Resources Password   | 56tzkOS9@$FERBGH  |


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
      <td>Web App Link</td>
      <td>
        <a href="https://app-retaildemo-prod.azurewebsites.net/" target="_blank">
          https://app-retaildemo-prod.azurewebsites.net/
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
    <tr>
      <td>Open the link In a new Private Window in a Browser	</td>
      <td>
        <a href="https://storagep7cjlb2iaspd2.blob.core.windows.net/retail/Data%20&%20AI%20Retail%20DREAM%20Demo%202.0.html" target="_blank">
          https://storagep7cjlb2iaspd2.blob.core.windows.net/retail/Data%20&%20AI%20Retail%20DREAM%20Demo%202.0.html
        </a>
      </td>
    </tr>
    <tr>
      <td>Customer Insights URL</td>
      <td>
        <a href="https://home.ci.ai.dynamics.com/app/home?instanceId=f1c61041-542a-4056-9f09-0c4992ccf773" target="_blank">
          https://home.ci.ai.dynamics.com/app/home?instanceId=f1c61041-542a-4056-9f09-0c4992ccf773
        </a>
      </td>
    </tr>
    <tr>
      <td>Azure Synapse Analytics URL</td>
      <td>
        <a href="https://web.azuresynapse.net/en-us/home?workspace=%2Fsubscriptions%2F506e86fc-853c-4557-a6e5-ad72114efd2b%2FresourceGroups%2FRetail2.0-Prod%2Fproviders%2FMicrosoft.Synapse%2Fworkspaces%2Fsynretailprod&relativePath=home" target="_blank">
          https://web.azuresynapse.net/en-us/home?workspace=%2Fsubscriptions%2F506e86fc-853c-4557-a6e5-ad72114efd2b%2FresourceGroups%2FRetail2.0-Prod%2Fproviders%2FMicrosoft.Synapse%2Fworkspaces%2Fsynretailprod&relativePath=home
        </a>
      </td>
    </tr>
    <tr>
      <td>Azure Data Explorer URL</td>
      <td>
        <a href="https://dataexplorer.azure.com/clusters/retaildataexplorer.synretailprod/databases/RetailDB" target="_blank">
          https://dataexplorer.azure.com/clusters/retaildataexplorer.synretailprod/databases/RetailDB
        </a>
      </td>
    </tr>
    <tr>
      <td>Azure Cosmos DB URL</td>
      <td>
        <a href="https://web.azuresynapse.net/en-us/authoring/explore/storageaccounts/synretailprod-WorkspaceDefaultStorage-stretailprod%2Fretailsynproddbbackup?subFolderPath=&workspace=%2Fsubscriptions%2F506e86fc-853c-4557-a6e5-ad72114efd2b%2FresourceGroups%2FRetail2.0-Prod%2Fproviders%2FMicrosoft.Synapse%2Fworkspaces%2Fsynretailprod" target="_blank">
          https://web.azuresynapse.net/en-us/authoring/explore/storageaccounts/synretailprod-WorkspaceDefaultStorage-stretailprod%2Fretailsynproddbbackup?subFolderPath=&workspace=%2Fsubscriptions%2F506e86fc-853c-4557-a6e5-ad72114efd2b%2FresourceGroups%2FRetail2.0-Prod%2Fproviders%2FMicrosoft.Synapse%2Fworkspaces%2Fsynretailprod
        </a>
      </td>
    </tr>
    <tr>
      <td>Azure PURVIEW URL</td>
      <td>
        <a href="https://web.purview.azure.com/resource/purviewretailprod?feature.tenant=f94768c8-8714-4abe-8e2d-37a64b18216a" target="_blank">
          https://web.purview.azure.com/resource/purviewretailprod?feature.tenant=f94768c8-8714-4abe-8e2d-37a64b18216a
        </a>
      </td>
    </tr>
    <tr>
      <td>Power Apps URL</td>
      <td>
        <a href="https://apps.powerapps.com/play/3de6c2f6-75b5-4877-a209-7fb8e27240a8?tenantId=f94768c8-8714-4abe-8e2d-37a64b18216a" target="_blank">
          https://apps.powerapps.com/play/3de6c2f6-75b5-4877-a209-7fb8e27240a8?tenantId=f94768c8-8714-4abe-8e2d-37a64b18216a
        </a>
      </td>
    </tr>
    <tr>
      <td>Form Recognizer ID Card</td>
      <td>
        <a href="https://stretailprod.blob.core.windows.net/labformrecognizer/idcard.jpg?sp=r&st=2022-03-31T23:20:36Z&se=2030-12-31T08:20:36Z&spr=https&sv=2020-08-04&sr=b&sig=aE49Edwuan0NqtG4pc41H%2FZw9Igy%2Btz91XdZZLttg9I%3D" target="_blank">
          https://stretailprod.blob.core.windows.net/labformrecognizer/idcard.jpg?sp=r&st=2022-03-31T23:20:36Z&se=2030-12-31T08:20:36Z&spr=https&sv=2020-08-04&sr=b&sig=aE49Edwuan0NqtG4pc41H%2FZw9Igy%2Btz91XdZZLttg9I%3D
        </a>
      </td>
    </tr>
    <tr>
      <td>Form Recognizer Invoice</td>
      <td>
        <a href="https://stretailprod.blob.core.windows.net/labformrecognizer/invoice.pdf?sp=r&st=2022-03-31T23:23:11Z&se=2030-12-31T08:23:11Z&spr=https&sv=2020-08-04&sr=b&sig=BgB1a02oLiLvuahYKLafTtVSEaDIMsbVQvXMXDhB9wQ%3D" target="_blank">
          https://stretailprod.blob.core.windows.net/labformrecognizer/invoice.pdf?sp=r&st=2022-03-31T23:23:11Z&se=2030-12-31T08:23:11Z&spr=https&sv=2020-08-04&sr=b&sig=BgB1a02oLiLvuahYKLafTtVSEaDIMsbVQvXMXDhB9wQ%3D
        </a>
      </td>
    </tr>
    <tr>
      <td>Form Recognizer Loyalty Form</td>
      <td>
        <a href="https://stretailprod.blob.core.windows.net/labformrecognizer/loyaltyform.png?sp=r&st=2022-03-31T23:23:59Z&se=2030-12-31T08:23:59Z&spr=https&sv=2020-08-04&sr=b&sig=rqEuE3AZzhmZDUUoaAUXBZcjk8WG43DguFOLgfLUqdk%3D" target="_blank">
          https://stretailprod.blob.core.windows.net/labformrecognizer/loyaltyform.png?sp=r&st=2022-03-31T23:23:59Z&se=2030-12-31T08:23:59Z&spr=https&sv=2020-08-04&sr=b&sig=rqEuE3AZzhmZDUUoaAUXBZcjk8WG43DguFOLgfLUqdk%3D
        </a>
      </td>
    </tr>
    <tr>
      <td>Form Recognizer Receipt</td>
      <td>
        <a href="https://stretailprod.blob.core.windows.net/labformrecognizer/receipt.png?sp=r&st=2022-03-31T23:24:42Z&se=2030-12-31T08:24:42Z&spr=https&sv=2020-08-04&sr=b&sig=mjrNqmBsSffsaxN5xr1sjFkabFheSHCczLy%2FaipK0v0%3D" target="_blank">
          https://stretailprod.blob.core.windows.net/labformrecognizer/receipt.png?sp=r&st=2022-03-31T23:24:42Z&se=2030-12-31T08:24:42Z&spr=https&sv=2020-08-04&sr=b&sig=mjrNqmBsSffsaxN5xr1sjFkabFheSHCczLy%2FaipK0v0%3D
        </a>
      </td>
    </tr>
  </tbody>
</table>
