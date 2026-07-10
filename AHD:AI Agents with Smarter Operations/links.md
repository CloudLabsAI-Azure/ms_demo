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
    <br> Fabric AI Operations Agent transforms Zava’s reactive operations into an intelligent, autonomous decision engine by orchestrating the "observe-analyze-decide-act" cycle across multiple AI agents. It eliminates operational inefficiencies by unifying data access through the Fabric Data Agent and enabling natural language-driven insights via Copilot. By coordinating specialized agents (Sales, Product, and Analyst) through Azure AI Foundry, it delivers real-time recommendations—such as inventory reallocation and promotion planning—empowering business users to proactively optimize operations, prevent stockouts, and maximize revenue with minimal manual intervention.
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
    <td>Microsoft Fabric Workspace</td>
    <td>
      <a href="https://app.fabric.microsoft.com/home" target="_blank">
        https://app.fabric.microsoft.com/home
      </a>
    </td>
    </tr>
  </tbody>
</table>



