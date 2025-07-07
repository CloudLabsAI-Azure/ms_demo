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
    This demo showcases how Modern Analytics in MIDP and Azure OpenAI Service can revolutionize the healthcare industry. The demo includes healthcare use cases and Payor scenarios, such as Call Center report analysis, transcript improvisation, and Member experience.
  </p>
  <ul>
    <li>Manage health data at scale.</li>
    <li>Apply machine learning and AI automation.</li>
    <li>Deploy easy-to-use AI tools for efficiency.</li>
    <li>Implement workflows specifically designed for health data</li>
    <li>These technologies work together to <strong>accelerate clinical analysis</strong>, <strong>improve patient engagement</strong>, and <strong>accelerate data value</strong>.</li>
  </ul>
</div>

<div class="highlight-box">
  <strong>IMPORTANT:</strong><br>
  Please launch the demo <strong>15 minutes before presenting</strong>. Resources may take a few minutes to provision.<br>
  ODL access provisioning may take <strong>5–7 minutes</strong>.<br>
  If unauthorized errors occur, wait a few minutes and then press <strong>Ctrl + Shift + R</strong> to refresh.<br>
  Please ensure you're signed out of any personal Microsoft accounts before logging in with the demo credentials.
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
      <td>Web App Link</td>
      <td>
        <a href="https://app-health-care-demo-v2prod.azurewebsites.net/" target="_blank">
          https://app-health-care-demo-v2prod.azurewebsites.net/
        </a>
      </td>
    </tr>
    <tr>
      <td>Microsoft Fabric Workspace</td>
      <td>
        <a href="https://app.powerbi.com/home?experience=fabric" target="_blank">
          https://app.powerbi.com/home?experience=fabric
        </a>
      </td>
    </tr>
    <tr>
      <td>Azure Synapse Analytics</td>
      <td>
        <a href="https://web.azuresynapse.net/en/home?workspace=%2Fsubscriptions%2F506e86fc-853c-4557-a6e5-ad72114efd2b%2FresourceGroups%2Frg-healthcare2-prod%2Fproviders%2FMicrosoft.Synapse%2Fworkspaces%2Fsynhealthcare2prod" target="_blank">
          https://web.azuresynapse.net/en/home?workspace=%2Fsubscriptions%2F506e86fc-853c-4557-a6e5-ad72114efd2b%2FresourceGroups%2Frg-healthcare2-prod%2Fproviders%2FMicrosoft.Synapse%2Fworkspaces%2Fsynhealthcare2prod
        </a>
      </td>
    </tr>
    <tr>
      <td>Azure Cosmos DB</td>
      <td>
        <a href="https://portal.azure.com/#@CloudLabsAIoutlook.onmicrosoft.com/resource/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-healthcare2-prod/providers/Microsoft.DocumentDB/databaseAccounts/cosmos-healthcare2-prod/dataExplorer" target="_blank">
          https://portal.azure.com/#@CloudLabsAIoutlook.onmicrosoft.com/resource/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-healthcare2-prod/providers/Microsoft.DocumentDB/databaseAccounts/cosmos-healthcare2-prod/dataExplorer
        </a>
      </td>
    </tr>
     <tr>
      <td>Azure ML Workspace</td>
      <td>
        <a href="https://ml.azure.com/?tid=f94768c8-8714-4abe-8e2d-37a64b18216a&wsid=/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourcegroups/rg-healthcare2-prod/providers/Microsoft.MachineLearningServices/workspaces/mlw-healthcare2-prod" target="_blank">
          https://ml.azure.com/?tid=f94768c8-8714-4abe-8e2d-37a64b18216a&wsid=/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourcegroups/rg-healthcare2-prod/providers/Microsoft.MachineLearningServices/workspaces/mlw-healthcare2-prod
        </a>
      </td>
    </tr>
    <tr>
      <td>Azure Databricks</td>
      <td>
        <a href="https://adb-6711778118362600.0.azuredatabricks.net/?o=6711778118362600#" target="_blank">
          https://adb-6711778118362600.0.azuredatabricks.net/?o=6711778118362600#
        </a>
      </td>
    </tr>
    <tr>
      <td>Microsoft Purview</td>
      <td>
        <a href="https://web.purview.azure.com/resource/purviewhealthcare2prod/main/catalog/home?feature.tenant=f94768c8-8714-4abe-8e2d-37a64b18216a" target="_blank">
          https://web.purview.azure.com/resource/purviewhealthcare2prod/main/catalog/home?feature.tenant=f94768c8-8714-4abe-8e2d-37a64b18216a
        </a>
      </td>
    </tr>
    <tr>
      <td>Azure EventHub</td>
      <td>
        <a href="https://portal.azure.com/#@CloudLabsAIoutlook.onmicrosoft.com/resource/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-healthcare2-prod/providers/Microsoft.EventHub/namespaces/evh-patient-monitoring-prod/overview" target="_blank">
          https://portal.azure.com/#@CloudLabsAIoutlook.onmicrosoft.com/resource/subscriptions/506e86fc-853c-4557-a6e5-ad72114efd2b/resourceGroups/rg-healthcare2-prod/providers/Microsoft.EventHub/namespaces/evh-patient-monitoring-prod/overview
        </a>
      </td>
    </tr>
  </tbody>
</table>
