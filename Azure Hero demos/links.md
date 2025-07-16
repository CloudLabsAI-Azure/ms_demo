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
    <br> This demo showcase how Zava a fictitious Retail Store serving suburban communities modernizes its operations through four interconnected real-time scenarios while preserving the customer's trusted and local experience. With rising customer expectations, siloed data, aging systems, and the rapid evolution of AI, Zava turns to Microsoft’s end-to-end cloud and AI platform to fuel its next chapter of growth.  At every step, the demo showcases how Microsoft Fabric, Azure OpenAI, Microsoft Purview, Copilot, and Azure infrastructure come together to empower Zava’s teams, unlock real-time insights, and deliver smart, secure, and deeply personalized retail experiences.<br> Imagine what you can do with real-time insights, AI-powered copilots, and trusted data governance for your organization!
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
        <a href="https://app-azureherodreamdemos.azurewebsites.net/" target="_blank">
          https://app-azureherodreamdemos.azurewebsites.net/
        </a>
        <button onclick="copyToClipboard()" style="background: none; border: none; cursor: pointer; padding-left: 10px;">
          <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="currentColor" viewBox="0 0 16 16">
            <path d="M10 1.5A1.5 1.5 0 0 1 11.5 3v1h-1V3a.5.5 0 0 0-.5-.5h-6A.5.5 0 0 0 3.5 3v9a.5.5 0 0 0 .5.5H6v1H4a1.5 1.5 0 0 1-1.5-1.5v-9A1.5 1.5 0 0 1 4 1.5h6z"/>
            <path d="M7 4a1 1 0 0 0-1 1v9a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1H7zm0-1h6a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2z"/>
          </svg>
        </button>
      </td>
    </tr>
    <script>
    function copyToClipboard() {
      const link = document.getElementById('demoLink').href;
      navigator.clipboard.writeText(link);
    }
    </script>
    <tr>
    <td>Azure AI Foundry</td>
    <td>
        <a href="https://ai.azure.com/foundryProject/overview?wsid=/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.CognitiveServices/accounts/proj-azure-hero-demo-1a-resource/projects/proj-azure-hero-demo-1a-dev&tid=f94768c8-8714-4abe-8e2d-37a64b18216a" target="_blank">
          https://ai.azure.com/foundryProject/overview?wsid=/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.CognitiveServices/accounts/proj-azure-hero-demo-1a-resource/projects/proj-azure-hero-demo-1a-dev&tid=f94768c8-8714-4abe-8e2d-37a64b18216a
        </a>
    </td>
    </tr>
    <tr>
    <td>Azure App Service</td>
    <td>
        <a href="https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.Web/sites/app-azureherodemos-container/appServices" target="_blank">
          https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.Web/sites/app-azureherodemos-container/appServices
        </a>
    </td>
    </tr>
    <tr>
    <td>Azure OpenAI</td>
    <td>
        <a href="https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.CognitiveServices/accounts/aoai-herodemo-dev/overview" target="_blank">
          https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.CognitiveServices/accounts/aoai-herodemo-dev/overview
        </a>
    </td>
    </tr>
    <tr>
    <td>Search Service</td>
    <td>
        <a href="https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.Search/searchServices/srch-herodemodev/overview" target="_blank">
          https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.CognitiveServices/accounts/aoai-herodemo-dev/overview
        </a>
    </td>
    </tr>
    <tr>
    <td>Azure Cosmos DB account</td>
    <td>
      <a href="https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.DocumentDb/databaseAccounts/cosmosdb-herodemo-001/overview" target="_blank">
        https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.DocumentDb/databaseAccounts/cosmosdb-herodemo-001/overview
      </a>
    </td>
    </tr>
    <tr>
    <td>SQL database</td>
    <td>
      <a href="https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.Sql/servers/sqlserver-azurehero-demo/databases/sql-azurehero-demo/overview" target="_blank">
        https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.Sql/servers/sqlserver-azurehero-demo/databases/sql-azurehero-demo/overview
    </td>
    </tr>
    <tr>
    <td>Azure Migrate</td>
    <td>
      <a href="https://portal.azure.com/#view/Microsoft_Azure_Migrate/AmhResourceMenuBlade/~/serverGoal" target="_blank">
        https://portal.azure.com/#view/Microsoft_Azure_Migrate/AmhResourceMenuBlade/~/serverGoal
    </td>
    </tr>
    <tr>
    <td>Azure ARC</td>
    <td>
      <a href="https://portal.azure.com/#view/Microsoft_Azure_ArcCenterUX/ArcCenterMenuBlade/~/allresources" target="_blank">
        https://portal.azure.com/#view/Microsoft_Azure_ArcCenterUX/ArcCenterMenuBlade/~/allresources
    </td>
    </tr>
    <tr>
    <td>Parts Unlimited Webapp</td>
    <td>
      <a href="https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-app-modernization-demo/providers/Microsoft.Web/sites/partsunlimited-web023/appServices" target="_blank">
         https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-app-modernization-demo/providers/Microsoft.Web/sites/partsunlimited-web023/appServices
    </td>
    </tr>
    <tr>
    <td>Azure Database for PostgreSQL flexible server</td>
    <td>
      <a href="https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-app-modernization-demo/providers/Microsoft.DBforPostgreSQL/flexibleServers/zavapostgresql/overview" target="_blank">
         https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-app-modernization-demo/providers/Microsoft.DBforPostgreSQL/flexibleServers/zavapostgresql/overview
    </td>
    </tr>
    <td>SQL managed instance</td>
    <td>
      <a href="https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-app-modernization-demo/providers/Microsoft.Sql/managedInstances/mi-zavadb/overview" target="_blank">
        https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-app-modernization-demo/providers/Microsoft.Sql/managedInstances/mi-zavadb/overview
    </td>
    </tr>
    <td>Azure Databricks Service</td>
    <td>
      <a href="https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.Databricks/workspaces/adb-herodemo/overview" target="_blank">
        https://portal.azure.com/#@cloudlabsai.ms/resource/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.Databricks/workspaces/adb-herodemo/overview
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
    <td>Fabric Eventhouse</td>
    <td>
      <a href="https://app.powerbi.com/groups/644a4412-d11e-4c52-b984-e6f88ba57eca/databases/8d328e5c-61cb-479f-aac9-607374ceb5b4?experience=power-bi" target="_blank">
        https://app.powerbi.com/groups/644a4412-d11e-4c52-b984-e6f88ba57eca/databases/8d328e5c-61cb-479f-aac9-607374ceb5b4?experience=power-bi
    </td>
    </tr>
     <tr>
    <td>Fabric Lakehouse</td>
    <td>
      <a href="https://app.powerbi.com/groups/644a4412-d11e-4c52-b984-e6f88ba57eca/lakehouses/98c0efdb-87e7-43f8-917e-c07695ec30cc?experience=power-bi" target="_blank">
        https://app.powerbi.com/groups/644a4412-d11e-4c52-b984-e6f88ba57eca/lakehouses/98c0efdb-87e7-43f8-917e-c07695ec30cc?experience=power-bi
    </td>
    </tr>
  </tbody>
</table>
