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
  If unauthorized errors occur, wait a few minutes and then press <strong>Ctrl + Shift + R</strong> to refresh.<br>
  Databricks may take around <strong>30–40 minutes</strong> to become available to the ODL user. This is due to Databricks default behavior of syncing users every 40 minutes.<br>
 For Microsoft Fabric, once you login with the ODL user, please wait <strong>5 minutes</strong> and refresh the screen to see the Workspaces.
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
      </td>
    </tr>
    <tr>
    <td>Microsoft Foundry Scenario 2</td>
    <td>
        <a href="https://ai.azure.com/resource/agentsList?wsid=/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.CognitiveServices/accounts/prj-aifoundry-aibigenie-resource/projects/prj-aifoundry-aibigenie&tid=f94768c8-8714-4abe-8e2d-37a64b18216a#Threads" target="_blank">
          https://ai.azure.com/resource/agentsList?wsid=/subscriptions/3f01ab49-a56f-4ee7-97fa-d23155156b42/resourceGroups/rg-azurehero-demo-dev/providers/Microsoft.CognitiveServices/accounts/prj-aifoundry-aibigenie-resource/projects/prj-aifoundry-aibigenie&tid=f94768c8-8714-4abe-8e2d-37a64b18216a#Threads
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
    <td>Azure Databricks Service</td>
    <td>
      <a href="https://adb-3978525401455147.7.azuredatabricks.net/" target="_blank">
        https://adb-3978525401455147.7.azuredatabricks.net/
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


